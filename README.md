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
3. Get a shell inside a running Docker container:
```bash
docker exec -it <container_name_or_id> sh
```
4. Build a Docker service with Docker Compose and see which stage it is in:
```bash
docker compose build <service_name> --progress=plain
```
5. Build and run a single Docker image:
```bash
docker build -t new(any)_image_name .(Where the Dockerfile is)
```
6. Stop a running Docker image:
```bash
docker stop image_name
```
7. Run a Docker image:
```bash
docker run -p 3000:3000 --env-file .env image_name
```
