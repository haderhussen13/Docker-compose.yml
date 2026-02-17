# Docker-compose.yml
This repository contains a Docker Compose (v3.9) configuration for a simple application stack consisting of:

PostgreSQL (postgres:15) – Primary database

Redis (redis:7) – Caching layer

Backend (nginx:alpine) – Application backend service

Frontend (nginx:alpine) – Frontend service

The stack is designed for Docker Swarm deployment with multiple replicas and external overlay networks.
