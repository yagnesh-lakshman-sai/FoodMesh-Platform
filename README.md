# Wow Foods !! - Microservices Food Delivery Platform

Wow Foods !! is a distributed food ordering and delivery platform built using Spring Boot and Spring Cloud microservices architecture.

The system is designed to demonstrate how modern distributed applications can be built using independent microservices, service discovery, centralized configuration, and API gateway routing.

---

## Architecture

This project follows a microservices architecture where each business capability is implemented as an independent service.

Core infrastructure services:

- Config Server – centralized configuration management
- Eureka Server – service discovery
- API Gateway – request routing and entry point

Business services:

- User Management Service
- Restaurant Management Service
- Order Management Service
- Delivery Service

---

## System Flow

1. Client sends request through API Gateway
2. Gateway routes the request to the appropriate service
3. Services communicate with each other using service discovery
4. Configuration is fetched from Config Server
5. Order and delivery operations are processed across services

---

## Microservices

### API Gateway
Single entry point for all external requests. Routes requests to internal services.

### Config Server
Manages centralized configuration for all microservices.

### Eureka Server
Handles service registration and discovery.

### User Management Service
Handles user registration, authentication, and user profile management.

### Restaurant Management Service
Manages restaurants, menus, and food items.

### Order Management Service
Processes orders placed by users.

### Delivery Service
Handles delivery assignment and tracking.

---

## Tech Stack

Backend
- Java
- Spring Boot
- Spring Cloud

Microservices Infrastructure
- Eureka Server
- Spring Cloud Gateway
- Config Server

Build Tool
- Maven

Architecture
- Microservices
- REST APIs
- Service Discovery

---

## Key Features

- Microservices architecture
- Service discovery using Eureka
- Centralized configuration management
- API Gateway routing
- Independent scalable services
- Modular system design

---

## Learning Objectives

This project demonstrates:

- Building distributed systems with Spring Boot
- Implementing service discovery
- Creating an API Gateway
- Managing configuration in microservices
- Designing domain-driven microservices

---

## Author

Developed as a microservices architecture project to demonstrate distributed system design using Spring Boot and Spring Cloud.
