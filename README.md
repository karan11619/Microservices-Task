# Microservices Containerization Assessment

## Overview

This project demonstrates containerization and orchestration of a Node.js microservices application using Docker and Docker Compose.

The application contains four services:

- User Service - Port 3000
- Product Service - Port 3001
- Order Service - Port 3002
- Gateway Service - Port 3003

All services communicate through a shared Docker Compose network.

## Project Structure

```text
Microservices/
├── user-service/
│   ├── Dockerfile
│   ├── app.js
│   └── package.json
├── product-service/
│   ├── Dockerfile
│   ├── app.js
│   └── package.json
├── order-service/
│   ├── Dockerfile
│   ├── app.js
│   └── package.json
├── gateway-service/
│   ├── Dockerfile
│   ├── app.js
│   └── package.json
├── docker-compose.yml
└── README.md