# CryptoWalletV2 - Front
Application web de suivi de transactions crypto à usage personnel.

# Stack Front-end : 
- React pour la création de l'interface utilisateur. 
- Redux pour la gestion de l'état de l'application. 
- Web3.js pour la communication avec l'API de Binance. 
- Chart.js pour l'affichage des graphiques.

# Fonctionnalités : 
L'application permettra aux utilisateurs de suivre et d'afficher leur historique de transactions crypto. Les graphiques afficheront l'évolution de la valeur des transactions en fonction du temps ou d'autres paramètres. Les utilisateurs pourront gérer leur historique de transactions en effectuant des opérations CRUD (Create, Read, Update, Delete) via l'API RESTful du back-end.

## Prérequis

- [Node.js (version 19 ou ultérieure)](https://nodejs.org/)
- [Docker (recommandé)](https://www.docker.com/products/docker-desktop)

## Installation

1. Clonez ce dépôt sur votre machine locale :

``git clone git@github.com:PierreAbeille/CryptoWalletV2.git``

2. Accédez au répertoire du projet :

``cd crypto-wallet-v2``

3. Installez les dépendances du projet :

``npm install``

## Exécution du projet

### Utilisation de Node.js

Pour exécuter l'application à l'aide de Node.js, utilisez la commande suivante :

``npm start``

L'application sera accessible à l'adresse `http://localhost:3000`.

### Utilisation de Docker

Pour exécuter l'application à l'aide de Docker, suivez ces étapes :

1. Construisez l'image Docker à partir du fichier `Dockerfile` :

``docker build -t crypto-wallet-v2 .``

2. Exécutez un conteneur Docker à partir de l'image construite :

``docker run -p 3000:3000 crypto-wallet-v2``

L'application sera accessible à l'adresse `http://localhost:3000`.
