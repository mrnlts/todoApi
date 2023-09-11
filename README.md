# ToDoApi

The toDoApi is a simple To-Do List API built using ASP.NET Core framework. It provides endpoints for creating, reading, updating, and deleting items from a to-do list. The API is designed to be user-friendly and easily integratable with front-end applications.

![Alt text](https://imageio.forbes.com/specials-images/dam/imageserve/1092571024/960x0.jpg?height=474&width=711&fit=bounds")

## Getting Started

### Setup

1. Clone the repository

2. Open the project in Microsoft Visual Studio.

3. Press Ctrl+F5 to run the API. This will open the Swagger UI in your default web browser.

## Using the API
### Swagger UI
The API is documented using Swagger. Once you run the project, you can navigate to http://localhost:7216/swagger/index.html to see the Swagger UI. Here, you can view and interact with the available endpoints of the API.

### Endpoints

`GET /api/TodoItems`: Retrieves a list of all to-do items.

`GET /api/TodoItems/{id}`: Retrieves details of a specific to-do item by its ID.

`PUT /api/TodoItems/{id}`: Updates an existing to-do item.

`POST /api/TodoItems`: Creates a new to-do item.

`DELETE /api/TodoItems/{id}`: Deletes a to-do item by its ID.

## Next Steps
#### Connecting to Front-end UI
To provide a user-friendly interface for interacting with the API, I'd like to build a front-end application (e.g., using React, Angular, or Vue.js) and connect it to this API.

#### Connecting to SQL Database
To persist data beyond the application's runtime, I plan to replace the in-memory database with a SQL database.

#### Dockerizing the Project
Finally, I want to containerize the application to provide a lightweight runtime environment for the project that is consistent from host to host.