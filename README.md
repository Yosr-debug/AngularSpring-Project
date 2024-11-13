![Logo de Eventica](./Eventica (1).png)

# Eventica

## Description du Projet

**Eventica** est une application web permettant aux utilisateurs de naviguer dans une liste d'événements, de s'inscrire à des événements, et de donner leur avis après leur participation. Elle offre une interface intuitive et moderne, ainsi qu'un système de gestion backend robuste pour gérer les événements et les inscriptions.

Ce projet est basé sur une architecture moderne avec Angular pour le frontend et Spring Boot pour le backend, intégrés via des API REST et utilisant Docker pour simplifier le déploiement et la gestion du serveur backend.

## Table des Matières

- [Technologies Utilisées](#technologies-utilisées)
- [Fonctionnalités](#fonctionnalités)
- [Prérequis](#prérequis)
- [Installation et Exécution](#installation-et-exécution)
  - [Backend - Spring Boot](#backend---spring-boot)
  - [Frontend - Angular](#frontend---angular)
- [Structure du Projet](#structure-du-projet)
- [Utilisation](#utilisation)
- [Contributions](#contributions)
- [Licence](#licence)
- [Contact](#contact)

---

## Technologies Utilisées

- **Frontend** : Angular
- **Backend** : Spring Boot
- **Base de Données** : PostgreSQL (via Docker)
- **Outils de Déploiement** : Docker et Docker Compose

---

## Fonctionnalités

1. **Navigation dans la Liste des Événements** : Les utilisateurs peuvent visualiser tous les événements, filtrés par catégories, date, ou popularité.
2. **Inscription aux Événements** : Chaque utilisateur peut s’inscrire aux événements qui l’intéressent.
3. **Avis sur les Événements** : Les utilisateurs peuvent donner leur avis sur les événements auxquels ils ont participé, offrant des retours pour améliorer l'organisation future.

---

## Prérequis

Avant de commencer, assurez-vous d’avoir les éléments suivants installés :

- **Node.js** (version recommandée : >= 14.x)
- **Angular CLI** (version recommandée : >= 12.x)
- **Docker** (version recommandée : >= 20.x)
- **Docker Compose** (version recommandée : >= 1.27)

---

## Installation et Exécution

### Backend - Spring Boot

1. **Configuration de la Base de Données** : La base de données PostgreSQL est incluse dans le fichier `docker-compose.yml` et sera configurée automatiquement.
2. **Lancer le Serveur Backend avec Docker Compose** :
   
   Depuis le répertoire principal du projet, exécutez la commande suivante pour démarrer le serveur backend :
   ```bash

   docker-compose up -d

Le backend sera accessible à [http://localhost:8089](http://localhost:8089).


## Frontend - Angular

### Installer les Dépendances Angular
Depuis le dossier `frontend`, exécutez :

npm install
## Configuration de l'API dans Angular
Modifiez le fichier `environment.ts` dans `src/environments` pour pointer vers `http://localhost:8089`.

## Lancer le Serveur Frontend

ng serve
## Contact
Pour toute question, veuillez nous contacter à :

Email : yosr.abbassi@epfedu.fr
        , yasmine.bahroun@epfedu.fr

Merci d'avoir choisi Eventica !
