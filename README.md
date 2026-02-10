# Spring Boot RESTful API Assignment

A microservices-based RESTful API application built with Spring Boot 4.0.2 and Java 17.

## Project Structure

This project contains six independent REST API modules:

### 1. E-Commerce API (`/api/products`)
- Product management system
- CRUD operations for products

### 2. Library Management API (`/api/books`)
- Book catalog management
- CRUD operations for books

### 3. Restaurant Menu API (`/api/menu`)
- Menu item management
- CRUD operations for menu items

### 4. Student Registration API (`/api/students`)
- Student information management
- CRUD operations for student records

### 5. Task Management API (`/api/tasks`)
- Task tracking system
- CRUD operations for tasks

### 6. User Profile API (`/api/users`)
- User profile management
- CRUD operations for user profiles

## Technologies

- **Spring Boot**: 4.0.2
- **Java**: 17
- **Build Tool**: Maven
- **Dependencies**: Spring Web, Spring Boot Test

## Setup & Run

1. Clone the repository:
```bash
git clone https://github.com/Shemaplacide/Springboot_Assignment.git
cd Springboot_Assignment
git checkout restFull_api_26497
```

2. Build the project:
```bash
./mvnw clean install
```

3. Run the application:
```bash
./mvnw spring-boot:run
```

The application will start on `http://localhost:8080`

## API Endpoints

Each module provides standard REST endpoints:
- `GET` - Retrieve all items or specific item by ID
- `POST` - Create new item
- `PUT` - Update existing item
- `DELETE` - Remove item

## Configuration

Application properties can be configured in `src/main/resources/application.properties`

## Author

Student ID: 26497
