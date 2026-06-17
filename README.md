# TaskTracker1

This repository contains a backend and frontend for the Task Tracker application.

## Run the project

Install dependencies:

```bash
npm run install:all
```

Start the backend:

```bash
npm run start:backend
```

Start the frontend:

```bash
npm run start:frontend
```

Start both backend and frontend together:

```bash
npm run start:web
```

## Backend

The backend runs from `Backend/` and uses SQLite by default when no PostgreSQL environment variables are provided.

Example `.env` values (Backend/.env can be created):

```env
PORT=5003
DB_FALLBACK_SQLITE=true
```

## Frontend

The frontend runs from `Frontend/` on Vite default port `5173`.
