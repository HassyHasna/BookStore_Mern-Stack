# Full Stack Book Store

A full-stack bookstore application with functionalities like adding, deleting, showing, and editing books. The application includes both table and card views on the admin side. Built using the MERN stack (MongoDB, Express, React, Node.js).

## Features

- Add, delete, edit, and show books
- Admin-side table and card view
- REST API for CRUD operations
- Backend: Node.js, Express, MongoDB with Mongoose
- Frontend: React
- Postman used for API testing

## Tech Stack

- **Frontend:** React
- **Backend:** Node.js, Express
- **Database:** MongoDB (Mongoose)
- **Tools:** Postman for API testing, MongoDB Compass for database management

## Prerequisites

- Node.js
- MongoDB
- Postman (for API testing)

## Installation

1. **Clone the repository:**
    ```bash
    git clone <repository-url>
    ```
2. **Navigate to the project directory:**
    ```bash
    cd bookstore
    ```
3. **Install Node modules for both backend and frontend:**
    - Navigate to the backend directory:
      ```bash
      cd backend
      npm install
      ```
    - Navigate to the frontend directory:
      ```bash
      cd ../frontend
      npm install
      ```
      
4. **Set up the environment variables:**
   - Create a `.env` file in the `backend` directory with the following:
    ```env
    MONGO_URI=<your-mongodb-connection-string>
    PORT=5555
    ```

## Running the Application

1. **Run the server and client concurrently:**
   - In the root directory of your project (if using `npm-run-all`):
     ```bash
     npm run dev
     ```
   - If not using `npm-run-all`, start the backend and frontend separately:
     - **Backend:**
       ```bash
       cd backend
       npm start
       ```
     - **Frontend:**
       ```bash
       cd ../frontend
       npm start
       ```

## Usage

- Use the application to add, edit, delete, and display books.
- Admins can switch between table and card views for managing books.
- Use Postman for testing REST API endpoints.

## API Endpoints

- **GET /api/books** - Get all books
- **POST /api/books** - Add a new book
- **PUT /api/books/:id** - Edit a book
- **DELETE /api/books/:id** - Delete a book

## Notes

- Ensure MongoDB is running before starting the server.
- Use Postman to test the backend API endpoints.

## License

This project is licensed under the MIT License.
