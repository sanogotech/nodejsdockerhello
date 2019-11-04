# nodejsdockerhello
Projet Exemple  de base "Hello World"  avec NodeJs et Docker

# Etape 0
$ npm init 
$ npm install express --save

-Ajouter le fichier index.js

## Etape 1: Lancer l'application nodejs
node index.js

## l'Url
localhost:8081

## Build image docker
docker build -t nodejsdockerhello  .


## Lancer Docker
docker run -p 8081:8081  nodejsdockerhello
