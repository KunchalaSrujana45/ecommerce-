# 🛒 E-Commerce Backend System (Spring Boot)

🚀 Spring Boot | REST API | MySQL | JPA

---

## 📌 Project Overview

* Developed a backend system for an E-commerce application using Spring Boot
* Designed RESTful APIs for handling users, products, cart, and orders
* Followed layered architecture (Controller → Service → Repository)
* Focused on scalability, maintainability, and clean code practices

---

## 🚀 Features

### 👤 User Management

* User registration and login functionality
* Session-based authentication
* Secure user data handling

### 📦 Product Management

* Add new products
* Update existing products
* Delete products
* View all available products

### 🛒 Cart Management

* Add products to cart
* Update product quantity
* Remove items from cart
* View total cart details

### 📑 Order Management

* Place orders
* View order history

---

## 🛠️ Tech Stack

* **Backend:** Java, Spring Boot
* **Database:** MySQL
* **ORM:** Hibernate (JPA)
* **Build Tool:** Maven
* **Testing Tool:** Postman

---

## 🏗️ Project Structure

* controller → Handles API requests
* service → Business logic implementation
* repository → Database interaction using JPA
* entity → Database models
* dto → Data transfer objects

---

## ⚙️ Setup Instructions

### 1️⃣ Clone Repository

```bash
git clone https://github.com/KunchalaSrujana45/ecommerce-
```

### 2️⃣ Create Database

```sql
CREATE DATABASE ecommerce_db;
```

### 3️⃣ Configure application.properties

```properties
spring.datasource.url=jdbc:mysql://localhost:3306/ecommerce_db
spring.datasource.username=root
spring.datasource.password=yourpassword

spring.jpa.hibernate.ddl-auto=update
spring.jpa.show-sql=true
```

### 4️⃣ Run Application

```bash
mvn spring-boot:run
```

---

## 🔗 API Endpoints

### Authentication

* POST /auth/register
* POST /auth/login

### Products

* GET /products
* POST /products
* PUT /products/{id}
* DELETE /products/{id}

### Cart

* POST /cart/add
* GET /cart
* DELETE /cart/remove/{id}

### Orders

* POST /orders
* GET /orders

---

## 🔐 Security

* Session-based authentication
* Password encryption using BCrypt

---

## 📈 Future Enhancements

* JWT-based authentication
* Payment integration
* Pagination and filtering
* Role-based authorization

---


---
