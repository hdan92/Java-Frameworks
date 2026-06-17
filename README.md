# Java Frameworks Project (D287)

## Overview
This project was created as part of the WGU Java Frameworks course. It demonstrates the use of Spring Boot, Spring MVC, Thymeleaf, and an H2 in-memory database to build a full-stack Java web application using a layered architecture.

The project focuses on backend development concepts such as controllers, services, repositories, and entities while also integrating a basic front-end using Thymeleaf templates.

---

## Technologies Used
- Java
- Spring Boot
- Spring MVC
- Spring Data JPA
- Thymeleaf
- H2 Database
- Maven
- HTML
- CSS

---

## Features
- Spring Boot application setup
- MVC (Model-View-Controller) architecture
- Dynamic web pages using Thymeleaf
- In-memory H2 database for development and testing
- CRUD functionality (Create, Read, Update, Delete)
- Form handling and data binding
- Layered architecture (Controller, Service, Repository, Entity)

---

## Project Structure
src/main/java
- controllers
- services
- repositories
- entities
- D287Application.java

src/main/resources
- templates (Thymeleaf HTML files)
- static (CSS and assets)
- application.properties

---

## How to Run the Application

1. Clone the repository:
   git clone <your-repo-link>

2. Open the project in your IDE (IntelliJ IDEA recommended)

3. Allow Maven to install dependencies

4. Run the application from:
   D287Application.java

5. Open your browser and go to:
   http://localhost:8080

---

## H2 Database Console (if enabled)

Access the database console at:
http://localhost:8080/h2-console

Default credentials:
- JDBC URL: jdbc:h2:mem:testdb
- Username: sa
- Password: (blank)

---

## Key Learnings
- Building web applications using Spring Boot
- Implementing MVC architecture in Java
- Using Thymeleaf for server-side rendering
- Working with Spring Data JPA and repositories
- Structuring a layered Java application
- Understanding dependency injection in Spring

---

## Future Improvements
- Add Spring Security authentication
- Improve UI styling with Bootstrap or modern CSS
- Expand CRUD features for additional entities
- Migrate from H2 to a persistent database (MySQL/PostgreSQL)
- Add better validation and error handling
