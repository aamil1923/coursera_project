# Task API

A lightweight REST API for managing a personal task list, built with Node.js and Express.

## What it does

This project lets you create and manage tasks through simple HTTP requests. You can fetch your current task list, add new tasks, or remove ones you no longer need — all through a clean JSON interface.

## Endpoints

| Method | Route | Description |
|--------|-------|-------------|
| GET | `/tasks` | Retrieve all tasks |
| POST | `/tasks` | Add a new task |
| DELETE | `/tasks/:id` | Remove a task by its index |

## Getting started

**Install dependencies:**
```bash
npm install
```

**Run the server:**
```bash
npm start
```

The server will start on `http://localhost:3000`.

## Usage example

To add a task, send a POST request with a JSON body:

```json
{
  "task": "Learn API development"
}
```

You'll get back a confirmation along with the updated task list.

## Tech stack

- **Runtime:** Node.js
- **Framework:** Express v4

## Author

Sara Diwan
