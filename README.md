# Node.js REST API Example

This project is a simple REST API built with Express.js. It provides CRUD operations for a sample resource called `users`.

## Features
- Express.js server
- CRUD endpoints for users
- In-memory data storage (for demonstration)

## Getting Started

### 1. Install dependencies
```
npm install
```

### 2. Run the server
```
npm start
```

The API will be available at `http://localhost:3000`.

## Endpoints
- `GET /users` - List all users
- `GET /users/:id` - Get a user by ID
- `POST /users` - Create a new user
- `PUT /users/:id` - Update a user
- `DELETE /users/:id` - Delete a user

## Notes
- This is a demo project. Data is not persisted between restarts.
