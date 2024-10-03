# Gestion de Stock Multi-Dépôts - SODIM 🏢📦

![Node.js](https://img.shields.io/badge/Node.js-v14.x-green?logo=node.js)
![Angular](https://img.shields.io/badge/Angular-v12-red?logo=angular)
![Express.js](https://img.shields.io/badge/Express.js-^4.17.1-black?logo=express)
![Sequelize](https://img.shields.io/badge/Sequelize-v6-blue?logo=sequelize)
![MySQL](https://img.shields.io/badge/MySQL-v8.0.23-blue?logo=mysql)

## Description du Projet 📖

Ce projet est une application de gestion de stock multi-dépôts réalisée pour **SODIM** dans le cadre de mon stage. Elle permet de gérer efficacement les produits, les dépôts, les mouvements de stock et les quantités disponibles dans chaque dépôt. L'application est construite avec **Angular** pour le frontend et **Node.js** avec **Express** et **Sequelize** pour le backend.

## Fonctionnalités 🔥

- **Gestion multi-dépôts** : Suivi des stocks dans différents dépôts en temps réel.
- **Gestion des produits** : Ajout, suppression et visualisation des produits.
- **Mouvements de stock** : Suivi des mouvements de produits (entrées, sorties).
- **Authentification et sécurité** : Sécurisation des accès avec **JWT** (JSON Web Token).
- **Pagination des produits** : Affichage des produits avec système de pagination pour une meilleure lisibilité.

## Architecture 🏗️

L'application est divisée en deux parties :

- **Frontend** : Utilise **Angular** pour offrir une interface utilisateur moderne, dynamique et responsive.
- **Backend** : Utilise **Node.js**, **Express**, et **Sequelize** pour gérer les opérations CRUD et la communication avec la base de données **MySQL**.

### Schéma de l'Architecture

```bash
Angular (Frontend)
   |
   |----> Node.js + Express (Backend API)
                  |
                  |----> Sequelize (ORM)
                             |
                             |----> MySQL (Database)

Technologies Utilisées 🛠️

    Frontend :
        Angular 12
        HTML5, CSS3, TypeScript
        Bootstrap pour le design

    Backend :
        Node.js 14
        Express.js 4.17.1
        Sequelize 6
        MySQL 8.0.23

Prérequis ✅

Avant de lancer l'application, assurez-vous d'avoir installé :

    Node.js (version 14.x ou supérieure)
    Angular CLI (version 12.x)
    MySQL (pour la base de données)

Installation et Configuration 🚀
Backend (Node.js + Express)

    Cloner le dépôt :

    bash

git clone https://github.com/FitiavanaRazakarivony/Gestion-stock-multi-tache.git
cd backend

Installer les dépendances :

bash

npm install

Configurer la base de données : Créez un fichier .env dans le dossier backend et ajoutez vos configurations MySQL :

    Remarque : le login d'admin : admin@gmail.com

bash

DB_HOST=localhost
DB_USER=root
DB_PASSWORD=''
DB_NAME=stage

Lancer le serveur :

bash

    npm start

Frontend (Angular)

    Naviguer dans le dossier frontend :

    bash

cd frontend

Installer les dépendances :

bash

npm install

Lancer l'application Angular :

bash

    ng serve

        L'application sera disponible sur http://localhost:4200.

Usage 🖥️

    Authentification et Connexion
    L'accès à l'application est sécurisé par JWT. Vous devez d'abord vous connecter avec vos identifiants pour accéder aux différentes fonctionnalités.

    Gestion des Produits
    Depuis le tableau de bord, vous pouvez :
        Ajouter de nouveaux produits
        Modifier les informations existantes
        Supprimer un produit
        Visualiser les détails d'un produit

    Gestion des Mouvements de Stock
    Les mouvements de stock peuvent être ajoutés pour refléter les entrées et sorties dans chaque dépôt.

    Suivi Multi-Dépôts
    L'application permet une vue d'ensemble des stocks dans différents dépôts et assure l'intégrité des données avec des mises à jour en temps réel.

License 📄

Ce projet est sous licence MIT. Consultez le fichier LICENSE pour plus de détails.

Remerciements 🙏

      Je tiens à exprimer mes sincères remerciements à SODIM pour m'avoir donné l'opportunité de réaliser ce projet de gestion de stock multi-dépôts.
      Ce stage m'a permis d'acquérir des compétences pratiques en développement web full-stack et en gestion de base de données.
       Merci également à toute l'équipe pour leur soutien et leurs conseils tout au long de cette expérience enrichissante.
