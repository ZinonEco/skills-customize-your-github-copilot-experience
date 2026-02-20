# 📘 Assignment: Building REST APIs with FastAPI

## 🎯 Objective

Build a REST API using the FastAPI framework in Python. Learn to create endpoints, handle HTTP requests, and manage data for a simple application.

## 📝 Tasks

### 🛠️ Set Up FastAPI Project

#### Description
Install FastAPI and create a basic project structure with a root endpoint.

#### Requirements
Completed program should:

- Install FastAPI and Uvicorn
- Create a main.py file
- Define a root endpoint that returns a welcome message
- Run the server and verify it works

### 🛠️ Create CRUD Endpoints

#### Description
Implement Create, Read, Update, Delete operations for a simple resource, like items or tasks.

#### Requirements
Completed program should:

- Define a data model (e.g., using Pydantic)
- Create endpoints for GET, POST, PUT, DELETE
- Use in-memory storage (list or dict)
- Handle basic error cases

### 🛠️ Add Request Validation

#### Description
Add input validation and response models to ensure data integrity.

#### Requirements
Completed program should:

- Use Pydantic models for request/response
- Validate input data
- Return appropriate HTTP status codes
- Include example requests/responses