# Docker Cheatsheet

This is a cheatsheet for Docker commands and concepts.

## Table of Contents

- [Installation](#installation)
- [Basic Docker Commands](#basic-docker-commands)
- [Images](#images)
- [Containers](#containers)
- [Docker Compose](#docker-compose)

## Installation

- [Docker Desktop](https://www.docker.com/products/docker-desktop) - Install Docker Desktop for Windows and macOS.
- [Docker Engine](https://docs.docker.com/engine/install/) - Install Docker Engine on Linux.

## Basic Docker Commands

- `docker --version` - Check the installed Docker version.
- `docker info` - Display Docker system information.
- `docker --help` - Get help and see a list of Docker commands.

## Images

- `docker pull IMAGE_NAME` - Pull an image from a registry.
- `docker build -t IMAGE_NAME PATH` - Build an image from a Dockerfile.
- `docker images` - List available Docker images.
- `docker rmi IMAGE_NAME` - Remove an image.

## Containers

- `docker run --name CONTAINER_NAME IMAGE_NAME` - Automatically creates container & run a container from an image with a custom name.
- `docker ps` - List running containers.
- `docker ps -a` - List all containers (running and stopped).
- `docker stop CONTAINER_ID` - Stop a running container.
- `docker start CONTAINER_ID` - Start a stopped container.
- `docker restart CONTAINER_ID` - Restart a container.
- `docker rm CONTAINER_ID` - Remove a container.
- `docker logs CONTAINER_ID` - View container logs.

# Using CONTAINER_NAME
- `docker stop CONTAINER_NAME` - Stop a running container using its name.
- `docker start CONTAINER_NAME` - Start a stopped container using its name.
- `docker restart CONTAINER_NAME` - Restart a container using its name.
- `docker rm CONTAINER_NAME` - Remove a container using its name.
- `docker logs CONTAINER_NAME` - View container logs using its name.

## Docker Compose

- `docker-compose up` - Start services defined in a `docker-compose.yml`.
- `docker-compose down` - Stop and remove containers defined in a `docker-compose.yml`.
- `docker-compose build` - Build services defined in a `docker-compose.yml`.
- `docker-compose ps` - List containers managed by Docker Compose.

## Conclusion

This cheatsheet provides a quick reference for common Docker commands and concepts, including how to specify a custom name for a container using the `--name` flag.
