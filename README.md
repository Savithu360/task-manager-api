# Task Manager API

A secure REST API built with Spring Boot and JWT authentication.

## Features

- User registration and login
- JWT authentication
- Secure endpoints with Spring Security
- CRUD operations for tasks
- Tasks linked to authenticated users
- MySQL database integration

## Tech Stack

- Java
- Spring Boot
- Spring Security
- JWT
- MySQL
- Hibernate / JPA

## API Endpoints

### Authentication

POST /api/auth/register  
POST /api/auth/login  

### Tasks

POST /api/tasks  
GET /api/tasks  
PUT /api/tasks/{id}  
DELETE /api/tasks/{id}

## Run the project

```bash
mvn spring-boot:run
