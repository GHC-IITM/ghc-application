# ghc-application

API LINK: https://ghc-applications-api.vercel.app/

# Todo API

This is a simple Todo API built with Express.js and Prisma.

<!-- ## Installation

1. Clone the repository: `git clone https://github.com/yourusername/yourrepository.git`
2. Install the dependencies: `npm install`
3. Start the server: `npm start` -->

## API Endpoints

### GET `/todos`

Fetches all todos.

### POST `/todos`

Creates a new todo.

Request body:

```json
{
    "title": "string"
}
```

### PUT `/updatetodos`
Updates a todo's completion status.

```json
{
    "id": "number",
    "completed": "boolean"
}
```

### DELETE `/todos/:id`
Deletes a todo.
