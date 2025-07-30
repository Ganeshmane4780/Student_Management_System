# 📚 Student Management System

A full-stack web application built using **Java Spring Boot**, **Thymeleaf**, and **MySQL**, designed to manage student records efficiently. This project supports **CRUD operations** via both **web interface** and **RESTful APIs**.

---

## 🚀 Features

- Add new student records
- View all students
- Update student information
- Delete student records
- RESTful API support for all CRUD operations
- Thymeleaf-based responsive UI

---

## 🛠️ Technologies Used

- **Java**
- **Spring Boot**
- **Spring Data JPA**
- **Thymeleaf**
- **MySQL**
- **RESTful APIs**
- **Maven**

---

## 🔧 Setup Instructions

1. **Clone the repository**
   ```bash
   git clone https://github.com/your-username/StudentManagementSystem.git
   cd StudentManagementSystem

2.  **Configure Database**

Create a MySQL database named studentdb and update your application.properties:

spring.datasource.url=jdbc:mysql://localhost:3306/studentdb?allowPublicKeyRetrieval=true&useSSL=false
spring.datasource.username=root
spring.datasource.password=yourpassword

3.  **Run the application**

./mvnw spring-boot:run


4.  **Access the application**

Web UI: http://localhost:8080/students

REST APIs:

GET /api/students

POST /api/students

PUT /api/students/{id}

DELETE /api/students/{id}



📁 Project Structure

src

├── main

│   ├── java

│   │   └── com.demo

│   │       ├── controller

│   │       ├── model

│   │       ├── repository

│   │       ├── service

│   │       └── StudentManagementSystemApplication.java

│   └── resources

│       ├── templates

│       ├── static

│       └── application.properties






📬 API Endpoints

Method  -  	Endpoint  - 	Description

GET  -   	/api/students  -	Get all students

GET  -  	/api/students/{id}  - 	Get student by ID

POST  - 	/api/students  - 	Add a new student

PUT  -  	/api/students/{id}  - 	Update a student

DELETE  - 	/api/students/{id}  - 	Delete a student
