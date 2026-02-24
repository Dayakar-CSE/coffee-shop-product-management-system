# Coffee Shop Product Management System

A layered Spring Boot MVC & REST web application for managing coffee shop products with database persistence, validation, and global exception handling.

## 🚀 Features

* Product CRUD operations (Create, Read, Update, Delete)
* Spring Boot MVC architecture with Thymeleaf UI
* REST API endpoints for product data
* Spring Data JPA database integration
* Form validation using Jakarta Validation
* Global exception handling
* Layered architecture (Controller → Service → Repository → Entity)

## 🧱 Tech Stack

* Java
* Spring Boot
* Spring MVC
* Spring Data JPA
* Thymeleaf
* H2/MySQL
* HTML / CSS

## 📂 Architecture

Controller → Service → Repository → Database

## 🌐 MVC Endpoints

* `/` — Product list
* `/showNewProductForm` — Add product
* `/showFormForUpdate/{id}` — Update product
* `/deleteProduct/{id}` — Delete product

## 🔗 REST API

* `GET /api/products` — Get all products
* `GET /api/products/{id}` — Get product by ID

## ⚠️ Exception Handling

Custom exception: `ProductNotFoundException`
Global handler returns:

* MVC → error page
* REST → HTTP 404

## ✅ Validation

Product fields validated using:

* `@NotNull`
* `@Size`
* `@Min`

## 📌 Learning Outcomes

This project demonstrates:

* Layered Spring Boot architecture
* REST + MVC integration
* JPA persistence
* Validation & error handling
* CRUD web application design

## 👨‍💻 Author

Dayakar — Java Backend Developer (in progress)
