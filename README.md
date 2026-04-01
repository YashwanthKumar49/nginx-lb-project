# Nginx Load Balancer - Docker Project

A load balancing setup using Nginx + Docker Compose.

## Architecture
User → Nginx LB → backend1 (5000) / backend2 (5001) / backend3 (5002)

## Usage
```bash
docker-compose up --build -d
```
