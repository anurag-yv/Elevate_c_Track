Create a REST API to Manage a List of Books Using Node.js and Express

### 🚀 Objective
Build a simple REST API with endpoints for CRUD operations on books (no database needed, store in memory).

- **Tools Used**: Node.js (free), VS Code, Postman (free)
- **Deliverables**: A Node.js Express server with endpoints: GET, POST, PUT, DELETE

### 🛠 Hints/Mini Guide
1. Initialize project with `npm init`.
2. Install Express (`npm install express`).
3. Setup basic Express server on port 3000.
4. Create an array to store book objects `{id, title, author}`.
5. Implement GET `/books` to return all books.
6. POST `/books` to add a new book from request body.
7. PUT `/books/:id` to update a book by ID.
8. DELETE `/books/:id` to remove a book.
9. Test endpoints with Postman.

### 🎉 Outcome
Understand REST API basics, Express routing, HTTP methods, and JSON handling.

## 📋 Interview Questions
1. What is REST?
2. What are HTTP methods and their use?
3. How do you handle routes in Express?
4. What is middleware in Express?
5. How do you parse JSON in Express?
6. What status codes do you use for CRUD?
7. How would you handle errors in Express?
8. What is CORS?
9. Explain request and response objects in Express.
10. How do you test API endpoints?

## 🔑 Key Concepts
- REST API
- Express.js
- HTTP methods
- JSON
- Middleware
- CRUD

## 🚀 Getting Started

### 📦 Installation
1. Clone this repository:
   ```bash
   git clone <your-repo-link>
   ```
2. Navigate to the project folder:
   ```bash
   cd <project-folder>
   ```
3. Install dependencies:
   ```bash
   npm install
   ```

### 🏃‍♂️ Running the Server
Start the server on port 3000:
```bash
npm start
```
- Access the API at `http://localhost:3000/books`.

### 🧪 Testing Endpoints
Use Postman to test the following endpoints:
- **GET /books**: Retrieve all books.
- **POST /books**: Add a book (e.g., `{"title": "Sample Book", "author": "Sample Author"}`).
- **PUT /books/:id**: Update a book (e.g., `{"title": "Updated Book"}` for ID 1).
- **DELETE /books/:id**: Delete a book (e.g., ID 1).

## 📂 Project Structure
- `app.js`: Main server file with Express routes.
- `package.json`: Project dependencies and scripts.
- `README.md`: This file!




