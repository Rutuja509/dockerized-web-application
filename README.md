# Dockerized Web Application on AWS EC2

## Project Overview

This project demonstrates how to containerize a Python Flask application using Docker and deploy it on an AWS EC2 instance.

## Technologies Used

- Python
- Flask
- Docker
- AWS EC2
- Git
- GitHub
- Ubuntu Linux

## Project Architecture

Developer (VS Code)
        ↓
Git & GitHub
        ↓
AWS EC2
        ↓
Docker Image
        ↓
Docker Container
        ↓
Python Flask Application
        ↓
Browser

## Project Files

- app.py
- Dockerfile
- requirements.txt
- .dockerignore

## Docker Commands Used

Build Docker Image

```bash
docker build -t docker-production-app:v1 .
```

Run Docker Container

```bash
docker run -d -p 5000:5000 --name docker-app docker-production-app:v1
```

Check Running Containers

```bash
docker ps
```

List Docker Images

```bash
docker images
```

Stop Container

```bash
docker stop docker-app
```

Start Container

```bash
docker start docker-app
```

## Deployment Steps

1. Created Python Flask application.
2. Wrote a Dockerfile.
3. Built Docker image.
4. Pushed source code to GitHub.
5. Created AWS EC2 Ubuntu instance.
6. Installed Docker on EC2.
7. Cloned GitHub repository.
8. Built Docker image on EC2.
9. Ran Docker container.
10. Accessed the application using EC2 Public IP.

## Learning Outcomes

- Docker Image Creation
- Docker Container Management
- Dockerfile
- Docker Port Mapping
- AWS EC2 Deployment
- Git and GitHub
- Linux Commands

## Author

Rutuja Wavhal