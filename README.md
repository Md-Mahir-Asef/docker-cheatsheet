# Docker Cheatsheet
This is a cheat sheet for Docker commands and Docker workflows.

## Common Docker Commands
1. See running containers:
```bash
docker ps
```
2. Run a Docker container with Docker Compose and get a shell inside that:
```bash
docker-compose -f <docker-compose-file-name> run --rm <service-name> sh
```
