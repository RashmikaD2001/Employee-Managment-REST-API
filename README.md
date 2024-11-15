## Employee Management REST API

This is a simple REST API for managing employee information, developed using Java and Spring Boot, with MySQL as the database.
Overview

The Employee Management REST API provides CRUD operations to manage employee data. It is implemented using the Spring Boot framework and follows the Spring MVC architecture pattern for a clean and modular structure.
Features

    Create new employee records
    Retrieve employee details
    Update existing employee information
    Delete employee records

Technologies Used

    Programming Language: Java
    Framework: Spring Boot
    Database: MySQL
    Architecture: Spring MVC

## Endpoints

The following endpoints are available for managing employees:

| HTTP Method | Endpoint            | Description                |
|-------------|----------------------|----------------------------|
| POST        | `/employees/add`     | Create a new employee      |
| GET         | `/employees`         | Retrieve all employees     |
| GET         | `/employees/{id}`    | Retrieve employee by ID    |
| PUT         | `/employees/{id}`    | Update employee by ID      |
| DELETE      | `/employees/{id}`    | Delete employee by ID      |

