#  Projet Fullstack - Gestion de Commandes des produits des clients

##  Introduction
Ce projet est une **application Fullstack** qui simule une interface de **pour la gestion des ventes**, permettant la gestion des **clients**, **produits**, et **commandes** avec un **calcul automatique du total TTC** et une **génération de ticket PDF**.

L’objectif est de comprendre et appliquer les bases du développement **Backend et Frontend**, tout en assurant une liaison efficace entre les deux pour gérer et afficher les données en temps réel.

##  Technologies utilisées et leur rôle

### 1- Backend
Le backend est responsable de la gestion des données et des interactions avec la base MongoDB. Il permet également de sécuriser l'accès aux ressources via l'authentification JWT.

- **Node.js** : Environnement d'exécution Javascript qui permet de créer un serveur rapide et efficace.
- **Express.js** : Framework léger permettant de créer facilement des API REST.
- **Mongoose** : ODM (Object Document Mapper) qui facilite l’interaction avec MongoDB.
- **MongoDB Compass/Atlas** : Outil graphique pour manipuler et visualiser les bases de données MongoDB.
- **CORS** : Middleware qui autorise les requêtes cross-origin entre le frontend et le backend.
- **JWT (JSON Web Token)** : Technologie permettant de sécuriser les sessions utilisateur.

### 2- Frontend
Le frontend est l'interface utilisateur qui permet aux utilisateurs d’interagir avec les fonctionnalités du système.

- **Angular** : Framework moderne qui facilite le développement d’interfaces dynamiques et réactives.
- **Bootstrap** : Framework CSS qui permet de créer des interfaces ergonomiques et responsives.
- **Tailwind CSS** : Framework CSS utilitaire pour personnaliser rapidement les styles.
- **RxJS** : Librairie utilisée par Angular pour gérer les flux asynchrones, notamment dans les requêtes API.

##  Fonctionnalités
- Gestion des **clients** et **produits** avec MongoDB  
- Interface dynamique avec **liste déroulante** pour clients et produits  
- Ajout/Suppression de **lignes de commande** (+ et -)  
- Calcul automatique du **TTC** basé sur le prix des produits et la TVA  
- Authentification sécurisée avec **JWT**  
- Génération et téléchargement du **ticket de commande en PDF**  

##  Installation


1-Clonez ce repository  

git clone https://github.com/Lorraine301/CC1_Technologie_Web2.git

2-Initialiser rapidement le projet Node.js avec:

**npm init -y**

3-Céez le dossier et installez les dépendances pour backend 

 **mkdir backend**

**npm install express mongoose cors dotenv body-parser**

4-Installez les dépendances  et créez le dossier pour pour frontend 

**npm install -g @angular/cli**

**ng new frontend**   

5-Créer la base de données dans MongoDB Compass/Atlas

6-Lancer le serveur

**node server.js**

7-Lancer Angular 

**ng serve**

## Conclusion

Ce projet est une excellente base pour apprendre à construire une application Fullstack complète. Il permet de maîtriser la liaison frontend-backend, d'améliorer les compétences en gestion de base de données MongoDB, et de comprendre l'authentification via JWT. 





