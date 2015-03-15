# JHipster and PostgreSQL database

This demo shows how to start in Docker a JHipster application with a PostgreSQL database using Docker Compose.

First, you need to install [Docker and Docker Compose](https://docs.docker.com/compose/#installation-and-set-up).

## Run the demo
To run the demo, you just need to start Docker Compose:
```
docker-compose up
```
This command creates two docker containers one for the database and another for the JHipster application.

You can access the application with the URL: [http://localhost:8080](http://localhost:8080)

You can check the containers status using the command:
```
docker-compose ps
```
