# Task API

A simple task manager API I built using Node.js and Express.

## About

I made this to practice building REST APIs. It's nothing fancy — you can add tasks, view them, and delete them. Everything is stored in memory so it resets when the server restarts, but it works well enough for learning purposes.

## How to run it

First, install the packages:

```bash
npm install
```

Then start the server:

```bash
npm start
```

It runs on port 3000, so just go to `http://localhost:3000`.

## Routes

* `GET /tasks` — returns the current list of tasks
* `POST /tasks` — adds a new task
* `DELETE /tasks/:id` — deletes a task by its index

## Adding a task

Send a POST request to `/tasks` with this in the body:

```json
{
  "task": "Learn API development"
}
```

It'll respond with the task that was added and the full updated list.

## Notes

No database, no auth — just a basic in-memory array. Good starting point if you're learning how Express routing works.

Built by Aamil Ghanchi

