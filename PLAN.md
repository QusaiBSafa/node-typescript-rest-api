# Infrastructure Overview
A REST API for managing users, built with Node.js, Express, and TypeScript.

## Data Models
- User: `id`, `name`, `email`

## API Design
- `GET /users`: Returns a list of users.
- `POST /users`: Creates a new user.
- `GET /users/:id`: Retrieves a user by ID.
- `PUT /users/:id`: Updates a user by ID.
- `DELETE /users/:id`: Deletes a user by ID.

## Key Decisions
- Using Express for simplicity and flexibility.
- Storing user data in memory for this example (can be replaced with a database).