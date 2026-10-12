# Car Management

A full-stack car showroom management application built with a Spring Boot backend, a frontend app, and a MySQL database dump for the car catalog.

## Overview

This repository is organized into three main parts:

- Backend: Java + Spring Boot REST API for managing cars
- Frontend: UI project (referenced as a separate frontend app)
- DataBase: MySQL database schema and sample data for the showroom

The application allows users to:
- Add new cars
- View all cars
- Fetch a single car by ID
- Update car information
- Delete a car record

## Tech Stack

### Backend
- Java
- Spring Boot 4.1.1
- Spring Data JPA
- MySQL Connector/J
- Maven

### Frontend
- Frontend project is present under `Frontend/car-frontend`

### Database
- MySQL
- Schema file: `DataBase/car_database.sql.sql`

## Project Structure

```text
Car_Management/
├── Backend/
│   └── Car/
│       ├── src/
│       ├── pom.xml
│       ├── mvnw
│       ├── mvnw.cmd
│       └── .mvn/
├── Frontend/
│   └── car-frontend
├── DataBase/
│   └── car_database.sql.sql
├── .gitignore
└── README.md
