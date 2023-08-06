# Docker Compose Setup for Spring Boot, MySQL, Kafka, and ELK Stack

This repository provides a Docker Compose setup for a complete application stack featuring Spring Boot, MySQL, Apache Kafka with Zookeeper, and the ELK stack (Elasticsearch, Logstash, Kibana).

## Configuration Steps

### 1. Provide Your Own Spring Boot App Image

- Replace `your-spring-app-image:tag` in `docker-compose.yml` with your own Spring Boot application Docker image and version tag.

### 2. Configure MySQL Root Password and Database name

- In the `docker-compose.yml` file, replace `DBname` with your own Database name.
- In the `docker-compose.yml` file, replace `<your-root-password>` with your own MySQL root password.

### 3. Start the Docker Stack

1. Open a terminal and navigate to the root directory of this repository.
2. Run the following command to start the Docker stack in detached mode:

   ```bash
   docker-compose up -d
