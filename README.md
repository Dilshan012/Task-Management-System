# Task Manager Application

## Project Description
This project is a full-stack web application that allows users to register, log in, and manage a list of tasks. The application uses Spring Boot for the back end and React.js for the front end. Authentication is implemented using JSON Web Tokens (JWT).

## Technologies Used
- **Back-End:**
  - Spring Boot
  - Spring Security
  - Spring Data JPA
  - JWT
  - MySQL (or H2 Database)
- **Front-End:**
  - React.js
  - Axios
  - Redux (or Context API)
  - Material-UI (optional)

## Features
- User registration and login
- Password hashing and secure storage
- JWT-based authentication
- CRUD operations on tasks
- Responsive UI

## Installation and Setup

## Prerequisites
- Java 11 or higher
- Node.js and npm
- MySQL (if not using H2 database)

## Front-End & Back-End Setup
- Clone the repository:
   ```bash
   git clone --recurse-submodules https://github.com/Dilshan012/Task-Management-System.git

## Back-End Setup
-  Navigate to the back-end directory: cd Back-End

- Configure the database in src/main/resources/application.properties:

### For MySQL Database
#### spring.application.name=taskmanagemantsystem
#### spring.datasource.url=jdbc:mysql://localhost:3306/tasks_management
#### spring.datasource.username=root
#### spring.datasource.password= >>YourPassword<<
#### spring.jpa.hibernate.ddl-auto=update
#### spring.datasource.driver-class-name=com.mysql.cj.jdbc.Driver
#### server.port=1010

- Run the Spring Boot application: ./mvnw spring-boot:run

## Front-End Setup
- Navigate to the front-end directory: cd Front-End/task-managemant-frontend

- Install dependencies: npm install

- Run the React application: npm start

## Running the Application
- Open your browser and navigate to http://localhost:3000.

- Register a new user and log in.

- Manage your tasks by adding, editing, and deleting them.
