# Countries TS

A TypeScript project for managing a collection of countries in a MongoDB database.

## What this project does

This project connects to MongoDB, clears the `paises` collection, and inserts a list of countries with their populations.

## Technologies

- TypeScript
- Node.js
- Express
- MongoDB
- cors

## Project structure

- `src/` - TypeScript source code
- `src/db/` - MongoDB connection
- `src/models/` - `Pais` model
- `src/routers/` - application routes
- `dist/` - compiled JavaScript files

## How to run

1. Install the dependencies:
   ```bash
   npm install
   ```

2. Compile the TypeScript code:
   ```bash
   npx tsc -p tsconfig.json
   ```

3. Run the project:
   ```bash
   node dist/index.js
   ```

> The project expects MongoDB to be running locally on port `27017` with the URI configured in `src/db/index.ts`.

## Notes

- This project was designed as a simple example to study the integration between TypeScript and MongoDB.
- To run it correctly, make sure the database is available before executing the script.
