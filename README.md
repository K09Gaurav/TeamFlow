 # 🧭 TeamFlow – Role-Based Task Management System
![TeamFlow_INTRO](SupportingFiles/TeamFlow_INTRO.png)

TeamFlow is a backend-driven task management system built with Spring Boot that demonstrates JWT & OAuth2 authentication, role-based access control, and modular REST API design — a simplified version of Jira built for clarity and backend mastery.

## 🚀 Features

Secure authentication with JWT and OAuth2 (GitHub/Google)

Role-based access: Admin, Manager, Team Lead, Team Member

CRUD APIs for Projects and Tasks

Layered architecture: Controller → Service → Repository → Entity

PostgreSQL database with JPA/Hibernate

Swagger UI for API documentation

Dockerized setup for both backend and database

Configurable via environment variables (.env support)

## 🧩 Tech Stack

Spring Boot | Spring Security | JPA/Hibernate | PostgreSQL | Docker | Lombok | Swagger/OpenAPI

## 🧠 Entities & Relationships

User ↔ Role: many-to-many

User ↔ Project: many-to-many

Project ↔ Task: one-to-many

Task ↔ User: many-to-one

## Setup

- Clone repository
`git clone https://github.com/yourusername/teamflow.git`

- Build and run using Docker
`docker-compose up --build`
