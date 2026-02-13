# 🚀 Food Inventory & Donation Management API

A production-ready RESTful backend system built using **Spring Boot** for managing food donations, inventory tracking, claim processing, and automated restock recommendations.

---

## 📌 Overview

The **Food Inventory & Donation Management API** is designed to manage food donation records efficiently while ensuring proper inventory tracking and stock validation.

It includes business logic for:
- Processing food claims
- Automatically updating stock levels
- Detecting low-stock items
- Generating restock recommendations

This project demonstrates clean backend architecture and real-world service-layer logic.

---

## 🛠 Tech Stack

- **Spring Boot**
- **Spring Data JPA (Hibernate)**
- **MySQL**
- **Swagger (OpenAPI)**
- **Lombok**
- **Maven**

---

## 🧱 Architecture

The project follows a layered architecture:

Controller → Service → Repository → Entity → Database

- **Controller Layer** – Handles REST endpoints
- **Service Layer** – Contains business logic
- **Repository Layer** – Database interaction via JPA
- **Entity Layer** – Maps objects to relational tables

---

## ✨ Key Features

### ➕ Add Food Donation
- Create new food records
- Store donor details, category, quantity, expiry date

### 📋 Retrieve Inventory
- Fetch all stored food items
- Filter by donor
- Filter by category

### 🔁 Claim Food
- Process claim requests
- Validate available stock
- Automatically reduce quantity
- Persist updated data in database

### 📉 Automated Restock Recommendation
- Detect low-stock items
- Identify items nearing expiry
- Generate system-based restock suggestions

## 📷 API Documentation

Interactive API documentation available via **Swagger UI**

Example endpoints include:

- `POST /api/food`
- `GET /api/food`
- `PUT /api/food/{id}/claim`
- `GET /api/food/restock-suggestions`

---

## ▶ Demo

https://github.com/user-attachments/assets/cfa3b03a-e00b-437f-b670-250a77092fdf

