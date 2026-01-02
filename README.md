# TP 32 : Mise en place d’un pipeline CI/CD microservices avec Jenkins, GitHub, SonarQube, Docker Compose et Ngrok

## Objectif

Mettre en place une chaîne CI/CD complète basée sur :

-GitHub (gestion du code)

-Jenkins (pipeline CI)

-SonarQube (analyse qualité & sécurité)

-Ngrok (exposition Jenkins vers Internet)

-GitHub Webhook (déclenchement automatique)

Le pipeline doit :

-Cloner le dépôt

-Compiler les microservices

-Lancer les analyses SonarQube pour car et client

-Exécuter les builds en parallèle

## Architecture

GitHub → Webhook → Ngrok → Jenkins → Maven Build → SonarQube


https://github.com/user-attachments/assets/2a320db0-a417-4d9b-b73d-ea9226bd27d9

