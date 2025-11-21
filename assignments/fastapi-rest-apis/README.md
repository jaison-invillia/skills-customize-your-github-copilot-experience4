# 📘 Assignment: Building REST APIs with FastAPI

## 🎯 Objective

Learn how to build RESTful APIs using the FastAPI framework. This assignment will guide you through creating endpoints, handling requests, and returning responses.

## 📝 Tasks

### 🛠️ Task 1: Setup FastAPI Project

#### Description
Set up a new FastAPI project in Python. Install the necessary dependencies and create a basic FastAPI application.

#### Requirements
Completed program should:

- Have FastAPI installed in a virtual environment
- Include a basic FastAPI app with a single endpoint `/` that returns a welcome message
- Be runnable using `uvicorn`

### 🛠️ Task 2: Create CRUD Endpoints

#### Description
Expand the FastAPI application to include CRUD (Create, Read, Update, Delete) endpoints for managing a resource (e.g., `items`).

#### Requirements
Completed program should:

- Include endpoints for creating, reading, updating, and deleting `items`
- Use a Python dictionary to store `items` temporarily
- Validate request data using Pydantic models

### 🛠️ Task 3: Add Query Parameters and Error Handling

#### Description
Enhance the API by adding query parameters to filter `items` and implement error handling for invalid requests.

#### Requirements
Completed program should:

- Support filtering `items` using query parameters
- Return appropriate HTTP status codes for errors (e.g., 404 for not found)
- Include error messages in the response body