# Commande utile pour Docker :

## Commande pour docker-machine :

* docker-machine create --drive nom_du_driver nom_machine : permet de créer la machine utilisant le driver nom_du_driver et ayant le nom nom_machine
* docker-machine ls : permet de lister les machines
* eval $(docker-machine env nom_machine) : permet d'assigner les variables spécifiques à l'environnement courant  du terminal
* docker-machine ip nom_machine : donne l'adresse IP
* docker-machine restart nom_machine : permet de redémarrer la machine 

## Commande pour docker :

* docker ps : visualiser les conteneurs actifs
* docker ps -a : visualiser tout les conteneurs
* docker stop nom_docker : permet de stopper un container
* docker rm nom_docker : permet de supprimer un container
* docker inspect nom_container : permet d'obtenir la configuration globale du conteneur
* docker pull nom_docker : permet de télécharger un container
* docker run nom_docker : permet de télécharger et de démarrer le container
* docker inspect -f '{{range.NetworkSettings.Networks}}{{.IPAddress}}{{end}}' nom_container : permet d'obtenir l'adresse IP du container

## Commande pour un volume :

* docker volume create nom_volume : permet la création d'un volume Docker
* docker volume ls : permet de lister les volumes docker créées

## Paramètres :

* --restart :permet de gérer les options de redémarrage du container
* --name : permet de donner un nom
* -d : fonctionne en tâche de fond
* -p : permet la configuration des ports utilisés
* -it : permet une interaction directe avec le container
* --rm : permet de stopper le container après arrêt de son utilisation

