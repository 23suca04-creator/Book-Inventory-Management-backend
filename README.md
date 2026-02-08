# Book Inventory Management System – Backend

This repository contains the backend implementation of the **Book Inventory Management System**, a full-stack CRUD-based web application designed to manage book inventory efficiently using modern development and DevOps practices.

The backend is built using **Spring Boot** and follows a layered architecture to provide clean separation of concerns, scalability, and maintainability.

---

## 🚀 Features

- RESTful APIs for Book Inventory Management
- CRUD operations:
  - Add a new book
  - View all books
  - Update book details
  - Delete a book
- Layered architecture (Controller, Service, Repository)
- Dockerized backend for portability
- Code quality analysis using SonarQube
- GitHub-based version control

---

## 🛠️ Tech Stack

- **Language:** Java  
- **Framework:** Spring Boot  
- **Build Tool:** Maven  
- **API Style:** REST  
- **Containerization:** Docker  
- **Code Quality:** SonarQube  
- **Version Control:** Git & GitHub  

---

## 🏗️ Project Structure

src/main/java
└── com.example.bookinventory
├── controller
├── service
├── repository
└── model


---

## 🔄 API Workflow

Client (Frontend)  
→ Sends HTTP request  
→ Spring Boot REST Controller  
→ Service Layer (Business Logic)  
→ Repository Layer (Data Handling)  
→ HTTP Response returned to client  

---

## ▶️ Run Backend Locally

### Prerequisites
- Java 17 or above
- Maven
- Docker (optional)

### Steps
```bash
git clone https://github.com/23suca04-creator/Book-Inventory-Management-backend.git
cd Book-Inventory-Management-backend
mvn spring-boot:run

🐳 Dockerization
Build Docker Image
docker build -t book-inventory-backend .

Run Docker Container
docker run -p 8080:8080 book-inventory-backend

🔍 Code Quality (SonarQube)

Static code analysis for bugs, vulnerabilities, and code smells

Quality gate ensures maintainable and reliable code

Supports refactoring and clean code practices

📌 Future Enhancements

Database optimization

Authentication & authorization

Role-based access control

Cloud deployment
