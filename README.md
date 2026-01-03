<img width="640" height="282" alt="2" src="https://github.com/user-attachments/assets/f498657d-7e58-45b2-b25c-3e7505a43617" /># TP21: Architecture Micro-services avec WebClient

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
   
<img width="634" height="313" alt="1" src="https://github.com/user-attachments/assets/10e79673-a515-4b4c-8083-8e678d1a098d" />


2. Lancer `service-client`.
   
   <img width="647" height="261" alt="3" src="https://github.com/user-attachments/assets/2eba536f-2c6b-4b3c-be77-d6137e255ee4" />


3. Lancer `service-car`.
   
<img width="640" height="282" alt="2" src="https://github.com/user-attachments/assets/97739a99-d19d-4164-98b7-5d190dcc154c" />
