# Attendance Service

Attendance Service is a **Spring Boot microservice** responsible for
tracking employee attendance data such as check-in, check-out,
and attendance summaries.

This service is designed as an **independent microservice**
with its own database and business logic.

---

## ✨ Features

- Employee check-in and check-out
- Date-based attendance filtering
- Monthly attendance summary
- Half-day and full-day attendance calculation
- Data consistency and validation
- Optimized database queries

---

## 🏗️ Architecture

- Layered architecture (Controller → Service → Repository)
- RESTful APIs
- Database-per-service design
- No direct dependency on other services' databases

---

## 🛠️ Tech Stack

- Java 17
- Spring Boot
- Spring Data JPA
- MySQL
- Maven
- Hibernate
- Flyway (for DB migrations)
- Swagger / OpenAPI (planned)

---
