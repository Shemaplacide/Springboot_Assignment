# Spring Boot RESTful API Assignment

## Introduction

This project demonstrates a complete microservices-based RESTful API system built with Spring Boot. It implements six independent API modules covering different business domains (E-Commerce, Library, Restaurant, Student Management, Task Management, and User Profiles). Each module provides full CRUD operations with additional filtering and search capabilities.

**Repository**: [https://github.com/Shemaplacide/Springboot_Assignment](https://github.com/Shemaplacide/Springboot_Assignment)

**Branch**: `restFull_api_26497`

## Student Information

- **Name**: Shemaplacide
- **Student ID**: 26497
- **Course**: Web Technology
- **Group**: Group C (Tuesday)

## Technologies Used

- **Spring Boot**: 4.0.2
- **Java**: 17
- **Build Tool**: Maven
- **Dependencies**: Spring Web, Spring Boot Test

## Project Structure

The project contains six independent REST API modules:

### 1. E-Commerce API (`/api/products`)
Manages product inventory with operations:
- Get all products, get by ID
- Filter by category, brand, stock status
- Search products by keyword

### 2. Library Management API (`/api/books`)
Handles book catalog with operations:
- Get all books, get by ID
- Search books by title

### 3. Restaurant Menu API (`/api/menu`)
Manages restaurant menu items with operations:
- Get all menu items, get by ID
- Filter by category and availability

### 4. Student Registration API (`/api/students`)
Manages student records with operations:
- Get all students, get by ID
- Filter by major and GPA

### 5. Task Management API (`/api/tasks`)
Tracks tasks with operations:
- Get all tasks, get by ID
- Filter by completion status and priority

### 6. User Profile API (`/api/users`)
Manages user profiles with operations:
- Get all users, get by ID
- Search by username, country, and age range

## Setup & Run

1. **Clone the repository**:
```bash
git clone https://github.com/Shemaplacide/Springboot_Assignment.git
cd Springboot_Assignment
git checkout restFull_api_26497
```

2. **Build the project**:
```bash
./mvnw clean install
```

3. **Run the application**:
```bash
./mvnw spring-boot:run
```

The application will start on `http://localhost:8082`

## Testing with HTML Interface

The project includes a `test.html` file for easy API testing without external tools like Postman.

### How to Use the HTML Testing Interface:

1. **Start the Spring Boot application** (must be running on port 8082)
2. **Open `test.html`** in any web browser
3. **Navigate through sections**:
   - Each section represents one API module (Library, Students, Menu, Products, Tasks, Users)
   - Click any button to test specific endpoints
   - Results appear in the output panel below in JSON format

### Features of the HTML Interface:
- **Organized by Module**: Each API is grouped in its own section
- **One-Click Testing**: No need to write URLs manually
- **Real-time Results**: See API responses instantly
- **Error Handling**: Shows connection errors if server is not running

### Example Tests Available:
- Get all items from any module
- Get specific items by ID
- Filter by categories, status, or other criteria
- Search functionality where applicable

This makes it easy for teachers and users to verify all API endpoints are working correctly.

## API Endpoints Summary

Each module provides standard REST operations:
- **GET** - Retrieve all items or specific item by ID
- **POST** - Create new item
- **PUT** - Update existing item
- **DELETE** - Remove item

Additional filtering and search endpoints are available per module (see Project Structure section).

## Configuration

Server port and other settings can be configured in:
`src/main/resources/application.properties`

## Conclusion

This assignment successfully implements a complete microservices architecture with six independent RESTful APIs. Each API follows REST principles with proper HTTP methods, status codes, and JSON responses. The included HTML testing interface provides an easy way to demonstrate and verify all functionality without requiring additional tools. All code is organized following Spring Boot best practices with clear separation between controllers and models.

## Author

**Shemaplacide** - Student ID: 26497  
Web Technology - Group C (Tuesday)
