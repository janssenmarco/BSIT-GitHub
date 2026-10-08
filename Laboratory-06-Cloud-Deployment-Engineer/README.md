## Mission Overview

This mission focused on deploying a private cloud application using Docker Compose. The deployment consisted of a Nextcloud application container and a MariaDB database container. Docker Compose was used to define and manage the multi-container infrastructure.

## Objectives

- Create a Docker Compose configuration for Nextcloud and MariaDB.
- Deploy a multi-tier application using Docker Compose.
- Configure Nextcloud to communicate with the MariaDB database.
- Access the Nextcloud web interface through port 8080.
- Properly stop and remove the deployed containers.
- Document the infrastructure and commands used during the mission.

## Skills Learned

- Creating and managing Docker Compose YAML files.
- Deploying multiple containers as a single application.
- Configuring communication between Docker containers.
- Using environment variables for database configuration.
- Mapping container ports to host ports.
- Checking container status using Docker Compose.
- Gracefully stopping and removing a multi-container deployment.
- Documenting cloud deployment infrastructure for other engineers.

## Commands Executed

```bash
mkdir nextcloud-deployment
cd nextcloud-deployment
nano docker-compose.yml
docker-compose up -d
docker-compose ps
docker-compose down

