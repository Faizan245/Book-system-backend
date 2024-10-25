# Book Recommendation System - Backend

## Overview
This is the backend component of the Book Recommendation System built with Node.js and Express. It connects to a MongoDB database and integrates authentication APIs to create a user, login a user, logout a user.

## Table of Contents
- [Technologies Used](#technologies-used)
- [Getting Started](#getting-started)
- [Project Structure](#project-structure)
- [API Endpoints](#api-endpoints)
- [API Documentation](#api-documentation)


## Technologies Used
- Node.js
- Express.js
- MongoDB
- Mongoose
- dotenv
- Swagger (for API documentation)

## Getting Started

### Prerequisites
Make sure you have the following installed on your machine:
- [Node.js](https://nodejs.org/) (v14 or higher)
- [npm](https://www.npmjs.com/) (comes with Node.js)
- MongoDB (either locally or a cloud instance)

### Initializing the Project

1. **Clone the Repository**

   git clone https://github.com/Faizan245/book-recommendation-system.git
   cd book-recommendation-system

   
2. **Install Dependencies Install the required packages:

    npm install

3. **Set Up Environment Variables Create a .env file in the backend directory and add the following environment variables:

    MONGO_URI=your_mongodb_connection_string
    GOOGLE_BOOKS_API_KEY=your_google_books_api_key
    PORT=5000

4. **Run the Backend Server Start the backend server:

    nodemon start



##Project Structure

backend/
├── models/
│   └── User.js
├── routes/
│   └── Auth.js
├── .env
├── package.json
└── index.js



##API Endpoints

*GET /api/books: Retrieve a list of all books.
*POST /api/books: Add a new book to the database.
*GET /api/books/:id: Get a specific book by ID.
*DELETE /api/books/:id: Delete a specific book by ID.



##API Documentation
API endpoints are documented using Swagger. You can access it at http://localhost:5000/api-docs after running the backend server.
   
