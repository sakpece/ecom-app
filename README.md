# ecom-app
ecommerce application backend 
---

About Spring Application 
---------------------
Application Structure
Entity Classes: Represent database tables.
DAO Layer: Interface and implementations for database access using JDBC.
Service Layer: Contains business logic.
Controller Layer: Handles HTTP requests.
Spring Security: Provides RBAC and JWT-based authentication/authorization.

Dependency Highlights
----------------------
Spring Boot Starter Web: Provides basic web functionalities (controllers, REST endpoints).
Spring Boot Starter Security: Manages authentication and authorization with Spring Security.
Spring Boot Starter Data JPA: Simplifies interaction with databases using JPA and Hibernate.
MySQL Driver: Enables communication with the MySQL database.
Lombok: Reduces boilerplate code by generating getter/setter methods, constructors, etc., during compilation.
JWT (JJWT): A lightweight library for creating and validating JWT tokens.
Spring Boot Starter Test: Includes tools for testing (JUnit 5, Mockito).

### **Features of This Ecom**
1. **RBAC Security:** Fine-grained access control using roles and permissions for secure application management.
2. **Scalability:** Hierarchical categories and products can handle large inventories.
3. **Extensibility:** Can add more modules like reviews, discounts, or a loyalty program.
4. **Audit Logs:** Tracks user actions for accountability and compliance.
5. **Payment Integration:** Supports multiple payment methods with status tracking.
