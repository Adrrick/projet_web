# Documentation du projet web.

Notre groupe est composé de 3 personnes : Tristan LEFEBVRE, Quentin DEMONTOUX et Hugo FERREIRA SILVA.

Nous étions parti sur le projet suivant qui était de reproduire le site de **"leboncoin"** composé obligatoirement de 5 pages dont : 
* **Une page recherche pour lister les annonces.**
* **Une page annonce qui fournit le descriptif de l'annonce sélectionnée.**
* **Une page de profil pour les membres connectés.**
* **Une page "mes annonces" pour les membres connectés, pour lister ses annonces.**
* **Une page "ajouter une annonce".**

Mais ce n'était pas la seule contrainte qu'on devait respecter puisque nous avions plusieur fonctionnalité obligatoire à implémenter dans notre site, comme : 
* **Un système de recherche d'annonces.**
* **Un système de messagerie .**
* **Un envoie de mail automatique pour débuter une nouvelle conversation.**
* **La possibilité de se créer un compte, se connecter et/ou modifier leur profil.**
* **La possibilité de poster une ou plusieurs annonce et les modifier.**

Malheureusement nous avons manqué de temps pour réalisé le système de messagerie ainsi que l'envoie de mail automatique.

Pour mener à bien notre projet nous avons utilisé **"xampp"** pour avoir un serveur apache qui permet de faire tourner notre site en local, ainsi que **"phpmyadmin"** pour nous permettre d'héberger notre base de donnée. Nous avons aussi utilisé plusieurs langages de programmation comme :
* **Le HTML/CSS.**
* **Le PHP.**
* **Le MySQL pour la BDD.**

## 1.Prérequis.

* xampp 3.2.4 sur le port 8080.
* phpmyadmin sur le port 3306.

## 2.Installation.

* Télécharger le zip contenant le fichier **"projet_web"** ainsi que le fichier SQL de la base de donnée.

## 3.Démarrage.

* Extraire l'archive et placer le dossier **"projet_web"** dans le dossier **"htdocs"** de votre dossier **"xampp"**.
* Créer une base de donnée nommée **"projet_web"** dans **"phpmyadmin"** et importer le fichier SQL dans l'archive, ce qui va crée les 3 tables de la base de donnée nécessaire au fonctionnement du site.
* Ouvrir un moteur de recherche puis entrer dans la barre de recherche **"localhost:8080/projet_web"**.
* Tester les fonctionnalités.