# Dockerized 2-Tier Web App with GitHub CI/CD

## Overview
This project demonstrates a 2-tier application consisting of a frontend (served by Nginx) and a backend (Node.js + Express), both containerized using Docker and deployed via GitHub Actions to a remote Linux VM.

## Folder Structure
- `frontend/`: Static HTML frontend
- `backend/`: Node.js API backend
- `.github/workflows/`: GitHub Actions CI/CD pipeline
- `docker-compose.yml`: Defines multi-container deployment

## Deployment Steps
1. Clone the repository.
2. Build and push Docker images.
3. Set GitHub secrets.
4. Push to main branch to trigger CI/CD.
5. Access your app via public IP on port 80.

## CI/CD Secrets Required
- `DOCKER_USERNAME`
- `DOCKER_PASSWORD`
- `SERVER_IP`
- `SERVER_USER`
- `SERVER_SSH_KEY`

## Screenshots
Include your deployment screenshots here.
