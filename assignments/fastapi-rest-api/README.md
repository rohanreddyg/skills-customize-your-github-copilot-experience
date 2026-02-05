# 📘 Assignment: Building REST APIs with FastAPI

## 🎯 Objective

Build a RESTful API using the FastAPI framework to learn modern web development, HTTP methods, and API design principles.

## 📝 Tasks

### 🛠️	Create a Basic API Server

#### Description
Set up a FastAPI application with basic endpoints that respond to HTTP requests. Your API will serve as the foundation for building more complex features.

#### Requirements
Completed program should:

- Import and initialize a FastAPI application
- Create a root endpoint (`/`) that returns a welcome message
- Create a `/health` endpoint that returns the API status
- Run the server using Uvicorn on port 8000
- Return proper JSON responses


### 🛠️	Implement CRUD Operations

#### Description
Build a simple task management API with Create, Read, Update, and Delete operations. Store tasks in a Python list (in-memory storage).

#### Requirements
Completed program should:

- Create a `POST /tasks` endpoint to add new tasks
- Create a `GET /tasks` endpoint to retrieve all tasks
- Create a `GET /tasks/{task_id}` endpoint to retrieve a specific task
- Create a `PUT /tasks/{task_id}` endpoint to update a task
- Create a `DELETE /tasks/{task_id}` endpoint to remove a task
- Use Pydantic models to validate request data
- Return appropriate HTTP status codes (200, 201, 404, etc.)


### 🛠️	Add Query Parameters and Error Handling

#### Description
Enhance your API with filtering capabilities and proper error handling to make it more robust and user-friendly.

#### Requirements
Completed program should:

- Add query parameters to the `GET /tasks` endpoint to filter by status (e.g., `?completed=true`)
- Implement proper error handling for invalid task IDs
- Return descriptive error messages with appropriate status codes
- Add input validation for task creation and updates
- Handle edge cases (empty lists, duplicate IDs, etc.)
