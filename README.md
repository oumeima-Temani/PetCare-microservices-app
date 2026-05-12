# PetCare Microservices App
PetCare Microservices App is a distributed system designed to manage pet care services through a scalable microservices architecture. The platform provides different services for appointments, veterinary management, alimentation, events, and user management.

---

## Features
- Microservices architecture with Spring Boot
- API Gateway for centralized routing
- Service discovery using Eureka
- Centralized configuration with Config Server
- Docker containerization
- User authentication and role management
- Appointment and veterinary management
- Pet alimentation and event services

---

## Tech Stack
- Java
- Spring Boot
- Angular
- Eureka Discovery Server
- API Gateway
- Config Server
- Docker & Docker Compose
- MySQL
- Maven

---

## Microservices
- UserMicroservice
- Pet_Care_Appointment
- Pet_Care_Animall
- Pet_Care_Service
- Pet_Care_veterinaire
- pet_care_alimentation
- pet_care_event

---

## Architecture
The application follows a microservices architecture:
- Eureka Server for service discovery
- API Gateway for routing requests
- Config Server for centralized configuration
- Independent services communicating through REST APIs

---

## Docker Deployment

### Run all services
```bash
docker-compose up --build