# TP21: Architecture Micro-services avec WebClient

Ce projet implémente une architecture micro-services utilisant Spring Cloud Netflix Eureka, Spring Data JPA (H2), et WebClient.

## Structure du projet

- **eureka-server** : Serveur de découverte (Port 8761).
- **service-client** : Micro-service de gestion des clients (Port 8081).
- **service-car** : Micro-service de gestion des voitures, communiquant avec `service-client` (Port 8082).

## Technologies utilisées
- Java 17
- Spring Boot 3.2.1
- Spring Cloud 2023.0.0
- H2 Database (In-Memory)
- Spring WebFlux (WebClient)
- Netflix Eureka

## Lancement
1. Lancer `eureka-server`.
2. Lancer `service-client`.
3. Lancer `service-car`.
