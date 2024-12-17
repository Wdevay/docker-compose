# Application Docker Compose

Ce projet utilise Docker Compose pour exécuter les services suivants :

- **Server** : Serveur backend (par exemple, Node.js, Express).
- **Client** : Application front-end (par exemple, React).
- **MongoDB** : Base de données MongoDB.

## Prérequis

Avant de lancer l'application, assurez-vous d'avoir les éléments suivants installés sur votre machine :

- **Docker** (https://www.docker.com/get-started)
- **Docker Compose** (généralement inclus avec Docker Desktop)

## Lancer l'application

Pour démarrer l'application en mode développement avec Docker Compose, utilisez la commande suivante :

```bash
docker compose -f compose.dev.yaml up --build
