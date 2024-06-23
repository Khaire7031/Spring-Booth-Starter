# Spring Booth Project

Spring Booth Project is a Spring Boot application that integrates with MySQL for data persistence, uses Thymeleaf for server-side rendering, and leverages Tailwind CSS and Flowbite for UI components.

## Prerequisites

- Java 11 or higher
- Maven
- Node.js and npm
- MySQL

## Getting Started

### 1. Clone the Repository

```bash
git clone https://github.com/yourusername/smartcontactmanager.git
cd smartcontactmanager

### 2. Application.properties

```bash
spring.application.name=scm
server.port=3000
spring.datasource.url=jdbc:mysql://localhost:3306/yourDatabaseName
spring.datasource.username=root
spring.datasource.password= your Password8
spring.datasource.driver-class-name=com.mysql.cj.jdbc.Driver
spring.jpa.hibernate.ddl-auto=update
spring.jpa.show-sql=true
