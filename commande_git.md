# Commande utile pour GIT

## Gestion utilisateur :

* git config --global user.email : ajouter une adresse mail
* git config --global user.name : ajouter un Nom et Prénom

## Lié un dossier à un repo GIT

Une fois dans le dossier cible :
* echo "#test" >> README.md
* git init
* git add README.md
* git commit -m "first commit"
* git branch -M main
* git remote add origin https://github.com/drnau/nom_repo_.git
* git push -u origin main

## Ajouter un nouveau fichier :

* git add nom_du_fichier
* git commit -m "commentaire"
* git push -u origin main

## Information sur les fichiers ajoutés sur GIT

* git status

## Gestion des branches :

* git checkout nom_de_la_branche : permet d'accéder à une branche
* git branch : permet de répertorier les branches du dépôt
* git merge nom_branche : permet de fusionner une branche avec celle active

## Suppression d'un fichier du repo :

* git rm nom_fichier 
