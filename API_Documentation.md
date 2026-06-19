# API Documentation

## Authentication APIs

### Register User

POST /api/auth/register

Request Body:
{
"fullName": "Dheepthi",
"email": "[dheepthi@test.com](mailto:dheepthi@test.com)",
"password": "123456"
}

### Login User

POST /api/auth/login

Request Body:
{
"email": "[dheepthi@test.com](mailto:dheepthi@test.com)",
"password": "123456"
}

## Project APIs

### Create Project

POST /api/projects

### Get All Projects

GET /api/projects

## Task APIs

### Create Task

POST /api/tasks

### Get All Tasks

GET /api/tasks
