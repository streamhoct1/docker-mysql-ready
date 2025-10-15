# Docker MySQL Ready Demo

This mini-project demonstrates a ready-to-use MySQL database container using Docker Compose. It sets up MySQL 8.0 with a database, user, and persistent volume.

## Description
- **docker-compose.yml**: Configuration for MySQL service with environment variables for root password, database, user, and password.
- **Ports**: Maps MySQL port 3306 for external access.
- **Volumes**: Persists data in mysql_data volume.

## Instructions
1. Install Docker and Docker Compose.
2. Run: `docker-compose up -d` to start the container in detached mode.
3. Connect to MySQL: `mysql -h localhost -P 3306 -u user -p` (password: pass).
4. Stop: `docker-compose down`.

Extend this by adding more services, networks, or connecting to an application.