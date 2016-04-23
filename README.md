# Containers
Various Docker containers

Configuration for personal services, tools, applications. They're mostly stored in Docker containers for convenience.

## Configuration

Critical configuration parts like exposed ports, paths, keys or secrets should be stored in environment variables or `.env` file.

## Commands

`docker-compose up`: Create and start containers (in foreground)

`docker-compose up -d`: Create and start containers (in background)

`docker-compose down`: Stop and remove containers, networks, images, and volumes

`docker-compose restart [SERVICE...]`: Restart services
