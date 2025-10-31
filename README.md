--Social Media
---Contexte

Ce projet a été développé dans le cadre du cahier des charges “My Social Networks”, inspiré du fonctionnement des réseaux sociaux modernes tels que Facebook.

L’objectif est de concevoir une API REST complète en Node.js, Express.js et MongoDB, permettant la gestion d’un réseau social moderne tout en respectant les bonnes pratiques REST, la validation des données et une architecture MVC claire et modulaire.

--Fonctionnalités principales

L’API permet la gestion de plusieurs ressources :

Utilisateurs : inscription, connexion, modification et suppression

Groupes : création et gestion de groupes publics, privés et secrets

Événements : création et gestion d’événements

Discussions et messages : gestion des fils de conversation et des messages

Albums, photos et commentaires

Sondages : création de questions, réponses et votes

Billetterie : création et gestion des tickets et types de tickets

--Technologies utilisées

Node.js

Express.js

MongoDB / Mongoose

Validator.js (validation des données)

Nodemon (mode développement)

Architecture MVC

ES Modules (import/export)

--Installation et démarrage

1--Cloner le projet

git clone https://github.com/Abderbess/Social_Media.git
cd Social_Media


2--Installer les dépendances

npm install


3--Configurer les variables d’environnement
Créer un fichier .env à la racine du projet :

MONGO_URI=mongodb+srv://<user>:<password>@<cluster>.mongodb.net/social_media
PORT=3000


4--Lancer le serveur

npm run dev


Le serveur démarre sur : http://localhost:3000

5--Documentation Postman

La documentation complète de l’API est disponible ici :
https://documenter.getpostman.com/view/26750234/2sB3Wny38c

Cette documentation permet de :

Visualiser toutes les routes disponibles

Tester les requêtes directement depuis Postman

Voir les schémas de données et les réponses possibles
