# List.it Server

Backend API for **List.it**, a social guessing game where authors submit statements made by people in a group and other players try to identify who said each one.

## What it does

- Serves the backend for the List.it application
- Handles application routes with Express
- Uses Prisma for database access
- Validates request data with Joi
- Supports local development with Nodemon

## Tech stack

- Node.js
- Express
- Prisma
- Joi

## Getting started

```bash
npm install
npm run dev
```

For a production-style start:

```bash
npm start
```

## Project structure

```text
src/
  app.js       Express application setup
  server.js    Server entry point
  routes/      API routes
prisma/        Prisma schema and database configuration
```

## About

This repository contains the server-side portion of List.it. I built it as part of a full-stack application project, with the backend separated from the client to keep the API and data layer independently maintainable.
