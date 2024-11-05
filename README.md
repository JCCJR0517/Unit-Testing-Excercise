# Simple User REST API with Spring Boot

This project is a simple REST API developed with Spring Boot. It demonstrates the basics of setting up a RESTful service, organizing a Spring Boot application, and writing unit tests for REST endpoints using MockMvc.

## Project Overview

This REST API allows you to:
- Retrieve a list of users
- Retrieve a specific user by ID

The project includes the following main components:
- **User Model**: Represents a user entity.
- **UserService**: Manages user data and business logic.
- **UserController**: Exposes REST endpoints for interacting with users.

## Project Structure

The project is organized as follows:
src 
  ├── main │
      ├── java │
          │ └── com.example.myapp │ │ 
                      ├── model │ 
                        │ └── User.java │ 
                      ├── service │ 
                        │ └── UserService.java │ 
                      │ └── controller │ 
                        │ └── UserController.java 
  └── test 
    └── java 
        └── com.example.myapp 
              └── controller 
                  └── UserControllerTest.java
pom.xml
