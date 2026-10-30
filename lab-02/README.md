# Lab 2: Book Management API

**Name:** K Manoj Sankar  
**Registration Number:** 252U1R9067  
**Section:** CSE-GEN-AI 2A 304

## Project Description

This project is a Book Management API built using Node.js and Express.js. It stores book data in SQLite and supports CRUD operations such as adding, listing, fetching by ID, updating, and deleting books.

## How to Run

### 1. Install Dependencies

```bash
npm install
```

### 2. Start the Server

```bash
npm run dev
```

or:

```bash
npm start
```

### 3. Open in Browser / Postman

```text
http://localhost:3000
```

## API Endpoints

| Method | Path | Description | Status Code |
|--------|------|-------------|-------------|
| GET | `/books` | Retrieve all books | 200 |
| GET | `/books/:bookId` | Retrieve a single book by ID | 200 |
| POST | `/books` | Add a new book | 201 |
| PUT | `/books/:bookId` | Update an existing book | 200 |
| DELETE | `/books/:bookId` | Delete a book by ID | 200 |

## Screenshots

### 1. Get All Books

![Get All Books](./screenshots/get-all-books.png)

### 2. Get Single Book

![Get Single Book](./screenshots/get-single-book.png)

### 3. Add Book (POST)

![Add Book](./screenshots/POST.png)

### 4. Update Book (PUT)

![Update Book](./screenshots/PUT.png)

### 5. Delete Book

![Delete Book](./screenshots/delete-book.png)

### 6. Database Verification

![Database Verification](./screenshots/database-verification.png)

## Notes

- The API uses SQLite for persistent book storage.
- All SQL queries are executed using parameterized statements.
- The project was tested using Postman for each CRUD operation.

## Technologies Used

- Node.js
- Express.js
- SQLite
- sqlite
- sqlite3
- Postman
- Git and GitHub
