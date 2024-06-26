
# User Management with Spring Boot

## Overview
This project provides RESTful APIs for managing users.

## How to Run
To run the application, execute the `DemoApplication.java` class.

## API Specifications

### Create User
- **Endpoint**: `POST http://localhost:8080/users`
- **Description**: Creates a new user.
- **Request Body**:
```json
{
  "username": "user_name",
  "email": "user_name@example.com"
}
```
- **Example Request**:
```
POST http://localhost:8080/users
Body:
{
  "username": "abcd",
  "email": "abcd@example.com"
}
```

### Get User by ID
- **Endpoint**: `GET http://localhost:8080/users/{id}`
- **Description**: Retrieves the user with the specified ID.
- **Example Request**: `GET http://localhost:8080/users/1`

### Get All Users
- **Endpoint**: `GET http://localhost:8080/users`
- **Description**: Retrieves all users.

### Delete User by ID
- **Endpoint**: `DELETE http://localhost:8080/users/{id}`
- **Description**: Deletes the user with the specified ID.       
