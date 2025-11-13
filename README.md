📝 Personal Task Management System

A RESTful Spring Boot application for managing personal tasks with full CRUD operations.
This project was built as a personal learning initiative to strengthen Java, Spring Boot, and OOP concepts through hands-on backend development.

🚀 Features

Create, read, update, and delete personal tasks

Manage users and their associated tasks

Filter tasks by status and priority

Centralized error handling and validation

API documentation using Swagger / OpenAPI

In-memory H2 database for development

Ready for PostgreSQL production setup

🧠 Learning Objectives

Reinforce core Java and OOP principles

Implement Spring Boot REST APIs

Practice clean service-repository architecture

Apply DTOs, custom exceptions, and unit testing

🏗️ Project Structure
task-manager/
├── src/
│   ├── main/
│   │   ├── java/com/taskmanager/
│   │   │   ├── controller/
│   │   │   ├── service/
│   │   │   ├── repository/
│   │   │   ├── model/
│   │   │   ├── dto/
│   │   │   └── exception/
│   │   └── resources/
│   │       ├── application.properties
│   │       └── data.sql
├── pom.xml
└── README.md

⚙️ Tech Stack
Component	Technology
Backend	Spring Boot 3.x
Database	H2 / PostgreSQL
Build Tool	Maven
Language	Java 17 / 21
Testing	JUnit 5, Mockito
Documentation	Swagger / OpenAPI
📡 API Endpoints
Task Management
Method	Endpoint	Description
GET	/api/tasks	Get all tasks
GET	/api/tasks/{id}	Get task by ID
POST	/api/tasks	Create a new task
PUT	/api/tasks/{id}	Update task
DELETE	/api/tasks/{id}	Delete task
GET	/api/tasks/status/{status}	Get tasks by status
User Management
Method	Endpoint	Description
GET	/api/users	Get all users
POST	/api/users	Create new user
GET	/api/users/{id}/tasks	Get user’s tasks
🧪 Testing

Unit tests for service layer using JUnit 5 and Mockito

Integration tests for repositories

Postman used for manual API testing

📘 Future Enhancements

User authentication and role management

Task categories and tags

Email reminders or notifications

React-based frontend interface

Docker containerization

👨‍💻 Author

Samidu Samarasinghe
📍 Sri Lanka
💬 Built as a personal learning project to explore Spring Boot and backend design patterns.
