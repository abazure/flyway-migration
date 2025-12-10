# Flyway Migration
This repository only for practice Flyway Migration tool.

## Getting Started
To get started with Flyway Migration, follow these steps:
1. Clone the repository to your local machine.
```shell
git clone 
```
2. Navigate to the project directory.
```shell
cd flyway-migration
```
3. Ensure you have Java and Maven installed on your machine.
4. Build the project using Maven.
```shell
mvn clean install
```
5. Run the docker-compose to start the database.
```shell
docker-compose up -d
```
6. Run the application.
```shell
mvn spring-boot:run
```
7. Flyway will automatically apply the migrations located in the `src/main/resources/db/migration` directory to the database.