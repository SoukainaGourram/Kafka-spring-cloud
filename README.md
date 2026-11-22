# Kafka Spring Cloud

Projet de démonstration d'une communication asynchrone entre microservices avec **Apache Kafka** et **Spring Cloud Stream**.

## Description

- **Producer** : publie des messages dans un topic Kafka.
- **Consumer** : écoute le topic et affiche les messages reçus.

## Technologies

- Java 17+
- Spring Boot / Spring Cloud Stream
- Apache Kafka
- Docker & Docker Compose
- Maven

## Lancement

1. Cloner le projet :
   ```bash
   git clone https://github.com/SoukainaGourram/Kafka-spring-cloud.git
   cd Kafka-spring-cloud
   ```

2. Démarrer Kafka :
   ```bash
   docker-compose up -d
   ```

3. Lancer les services (producer et consumer) :
   ```bash
   mvn spring-boot:run
   ```

## Auteure

Soukaina Gourram
