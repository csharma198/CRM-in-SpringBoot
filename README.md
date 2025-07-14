# CRM in Spring Boot

A full-stack Customer Relationship Management (CRM) application built using Spring Boot for managing customer data, authentication, and RESTful APIs. Designed to be scalable, secure, and easily extensible.

## 🚀 Features

- Customer CRUD (Create, Read, Update, Delete)
- Role-based user authentication (Admin/User)
- RESTful APIs with Spring MVC
- JWT-based login system (optional)
- MySQL/PostgreSQL database integration
- Docker support (optional)
- Frontend integration ready (React, Angular, or Thymeleaf)

## 🛠 Tech Stack

- **Backend**: Java 17+, Spring Boot, Spring MVC, Spring Data JPA
- **Database**: MySQL or PostgreSQL
- **Build Tool**: Maven
- **Tools**: VS Code, Git, GitHub
- **Optional**: Docker, Vaadin/React Frontend

## 📁 Project Structure

CRM-in-SpringBoot/
├── src/
│ ├── main/
│ │ ├── java/
│ │ │ └── com/example/crm/
│ │ │ ├── controller/
│ │ │ ├── service/
│ │ │ ├── model/
│ │ │ └── repository/
│ │ └── resources/
│ │ ├── application.properties
│ │ └── static/templates/
├── pom.xml
├── Dockerfile
├── .gitignore
├── README.md


## ⚙️ Configuration

### `application.properties`

```properties
spring.datasource.url=jdbc:mysql://localhost:3306/crmdb
spring.datasource.username=root
spring.datasource.password=yourpassword

spring.jpa.hibernate.ddl-auto=update
spring.jpa.show-sql=true
server.port=8080
