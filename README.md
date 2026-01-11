# Enterprise Document Management System

A production-style document management system built using ASP.NET Core
and Azure cloud services to demonstrate real-world enterprise backend development.

## Overview
This project simulates how modern enterprise applications handle secure
document storage, authentication, and scalable API design.
The focus is on backend architecture, clean code, and cloud integrations.

## Tech Stack
- ASP.NET Core Web API (.NET)
- C#
- Azure Blob Storage
- SQL Server
- JWT Authentication
- Role-Based Access Control (RBAC)
- Docker & Docker Compose
- Swagger / OpenAPI

## Architecture
The system follows a microservices-based architecture:

- **Auth Service**
  - Handles user authentication and JWT token generation
  - Manages user roles such as Admin and User

- **Document Service**
  - Secure document upload, retrieval, and deletion
  - Stores files in Azure Blob Storage
  - Stores metadata in SQL Server
  - Protected using JWT and role-based authorization

## Key Features
- Secure authentication using JWT tokens
- Role-based authorization for protected endpoints
- RESTful API design following best practices
- Azure Blob Storage integration for file handling
- Database-backed document metadata management
- Dockerized services for local development
- Swagger documentation for API testing

## How to Run
1. Clone the repository
2. Update connection strings in `appsettings.json`
3. Ensure Docker is running
4. Run:
5. Access the APIs using Swagger UI

## Why This Project
This project was built to demonstrate hands-on experience with
enterprise backend development using .NET and Azure, including
microservices, authentication, cloud storage, and secure API design.
