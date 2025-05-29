# 🎬 Springboard Microservices Project

This project demonstrates a modular microservices-based architecture using Spring Boot and Docker. The system simulates a movie platform composed of multiple independently deployable services.

## 📽️ Project Overview

The application includes:

- 🎞️ **Movie Service** – Stores and serves details such as movie name, director, and actors.
- ⭐ **Rating Service** – Manages user ratings, including individual reviews and average scores.

Each microservice is containerized using Docker and configured to work with different types of databases based on the environment.

## ⚙️ Key Features

- Microservices architecture with RESTful APIs
- In-memory H2 database for local development
- PostgreSQL for production-ready environments
- Dockerized deployment for each service
- Optimized database connectivity in containerized environments

## 🧱 Tech Stack

- Java + Spring Boot
- H2 (in-memory)
- PostgreSQL
- Docker
- REST API

## 🚀 Project Goals

- Build and deploy independent microservices
- Use Docker for seamless local and production deployment
- Demonstrate environment-specific database integration
- Follow a bottom-up development approach using Spring annotations and clean architecture

---

This project serves as a foundation for building scalable, containerized backend services and demonstrates key microservices principles using practical tools and techniques.
