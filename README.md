# E-Commerce Backend Project

##  Description

This project is a backend system for an e-commerce platform developed using Spring Boot. It includes user authentication, product management, cart management, order processing, and payment integration.

##  Features

###  Authentication & Authorization

* User registration and login
* JWT-based authentication using Spring Security
* Role-based authorization (User/Admin)

###  Product Management

* Create, update, delete, and view products
* Product attributes: name, description, price, stock quantity, image URL

###  Cart Management

* Add products to cart
* Update and remove items from cart
* Each user can manage only their own cart

###  Order Management

* Create orders from cart
* Store total price, shipping details, and payment status
* View order details

###  Payment Integration

* Implemented simulated payment processing
* Handles payment success and failure scenarios
* Updates order status accordingly
* Designed to be easily integrated with real payment gateways like Stripe or PayPal

##  Tech Stack

* Java
* Spring Boot
* Spring Security
* JWT
* MySQL
* JPA / Hibernate

##  Database Design

* One-to-Many: User → Orders
* Many-to-Many: Orders ↔ Products
* Cart linked with User and Products

##  Error Handling

* Proper validation for inputs
* Meaningful error messages
* HTTP status codes (200, 201, 400, 401, 404)

##  API Modules

* Auth APIs (Login/Register)
* Product APIs
* Cart APIs
* Order APIs
* Payment APIs

##  How to Run

1. Clone the repository
2. Configure MySQL database in `application.properties`
3. Run the Spring Boot application
4. Access APIs using Postman

##  Testing

* APIs tested using Postman

##  Author

Kiran Patkari
