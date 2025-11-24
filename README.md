# Microservices Spring Cloud

Ce projet contient trois services principaux dans une architecture microservices Spring Cloud :

## 1. API Gateway
- Rôle : Point d’entrée unique pour tous les clients, gère le routage vers les services backend.
- Exemple : **Spring Cloud Gateway**

## 2. Client Service
- Rôle : Service métier qui gère la logique pour les clients/utilisateurs.
- Exemple : **Spring Boot REST Service** avec base de données MySQL

## 3. Account Service
- Rôle : Service métier qui gère les comptes et la sécurité.
- Exemple : **Spring Boot REST Service** avec Spring Security
