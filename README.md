# Bookstore Project

## Overview

Bookstore is a full-stack dynamic and responsive web application designed to provide users with a seamless book browsing and purchasing experience. This project is crafted using the MERN stack: MongoDB, Express.js, React.js, and Node.js, with Tailwind CSS for UI design.

## Technologies Used

- **MongoDB**: A NoSQL database for storing book and user information.
- **Express.js**: A Node.js framework used for building the backend RESTful APIs.
- **React.js**: A JavaScript library for building the frontend user interface.
- **Node.js**: JavaScript runtime environment that allows us to run JavaScript on the server-side.
- **Tailwind CSS**: A utility-first CSS framework for designing a responsive and modern UI.

## Features

- **Book Catalog**: Browse a collection of books with detailed information.
- **User Authentication**: Register and login functionality with secure authentication.
- **Shopping Cart**: Add books to the cart and proceed to checkout.
- **Order Management**: View order history and order details.
- **Search Functionality**: Search for books by title, author, or genre.
- **Responsive Design**: Optimized for both desktop and mobile devices.

## Installation

1. **Clone the repository**:
    ```bash
    git clone https://github.com/yourusername/bookstore.git
    cd bookstore
    ```

2. **Backend Setup**:
    - Navigate to the backend directory:
      ```bash
      cd backend
      ```
    - Install backend dependencies:
      ```bash
      npm install
      ```
    - Create a `.env` file in the backend directory and add your MongoDB URI and other environment variables:
      ```plaintext
      MONGO_URI=your_mongodb_uri
      JWT_SECRET=your_jwt_secret
      ```
    - Start the backend server:
      ```bash
      npm start
      ```

3. **Frontend Setup**:
    - Navigate to the frontend directory:
      ```bash
      cd ../frontend
      ```
    - Install frontend dependencies:
      ```bash
      npm install
      ```
    - Start the frontend development server:
      ```bash
      npm start
      ```

4. **Visit the application**:
    - Open your browser and go to `http://localhost:3000` to view the application.

## Folder Structure

