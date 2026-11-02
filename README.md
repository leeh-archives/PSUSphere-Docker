# PSUSphere Docker

## Project Description

PSUSphere is a Django-based student organization management system. This repository contains the Docker configuration for running the project using containers.

## Requirements

- Docker Desktop
- Docker Hub account (for pulling the published image)

## Project Files

- `Dockerfile` – Instructions for building the Docker image.
- `.dockerignore` – Files excluded during the Docker build.
- `docker-compose.yml` – Configuration for building and running the application locally.
- `requirements.txt` – Python dependencies.
- `for_client/docker-compose.yml` – Configuration for running the published Docker Hub image.

## Running Locally

1. Clone this repository.
2. Open the project folder in your terminal.
3. Build and start the application:

```bash
docker compose up --build
```

4. Open your browser and visit:

http://localhost:8000

## Running Using Docker Hub

1. Make sure Docker Desktop is running.
2. Open a terminal inside the `for_client` folder.
3. Pull and start the application:

```bash
docker compose up -d
```

4. Open your browser and visit:

http://localhost:8000

## Docker Hub Image

[leeharchives/psusphere](https://hub.docker.com/r/leeharchives/psusphere)

## Stopping the Application

For the local configuration:

```bash
docker compose down
```

For the client configuration, run the same command inside the `for_client` folder.

## Developer

Leeh Vann Joshua M. Lomocso  
Ramaidha Digermo
