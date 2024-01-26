# CRUD-operations
This Spring Boot application exposes a REST API for basic CRUD operations on a Students table with fields like id, name, age, and grade. It utilizes an in-memory H2 database, allowing users to perform Select, Insert, Delete, and Update operations via HTTP requests.
# Spring Boot CRUD API - Students

## Overview
This project demonstrates a simple CRUD (Create, Read, Update, Delete) API for managing student records. It is implemented using Spring Boot and utilizes an in-memory H2 database.

## Features
- **GET (localhost:8080/students)** Retrieve a list of all students.
- **POST (localhost:8080/students)** Create a new student record.
- **PUT (localhost:8080/students/{id})** Update an existing student record.
- **DELETE (localhost:8080/students/{id})** Delete a student record.

## Project Structure
- **Student:** Entity class representing a student.
- **StudentRepository:** JPA repository for database operations.
- **StudentService:** Service class implementing CRUD operations.
- **StudentController:** REST controller mapping HTTP requests to service methods.

## Setup and Run
1. Clone the repository.
2. Open the project in your preferred IDE.
3. Run the application.
4. Access the API endpoints using tools like Postman or curl.
