# User Authentication System

## Overview

This project is a bare-bone backend service for a user authentication system built using `Node.js` and `MongoDB`. It provides essential functionalities for user registration, login, profile management, and comment posting through RESTful routes, with middleware for authentication and route protection. The service is tested using `Postman` for API functionality. There is no frontend component included in this repository.

## Features

- User Registration: Allows new users to sign up with their email and password.
- User Login: Authenticates users and generates a JWT token for session management.
- Profile Management: Users can view and update their profile.
- Comment Feature: Users can post and manage comments.
- JWT Protected Routes: Ensures only authenticated users can access private routes.

## Backend Development

- RESTful Routes: Designed and implemented routes for registration, login, profile management, and comments. These routes are integrated with MongoDB for efficient data storage.
- Middleware for Authentication: Implemented middleware to protect private routes and ensure only authorized users can log in, update profiles, and post comments.
- API Testing with Postman: Used Postman to test the backend APIs, including GET and POST requests for user data and comments. Token-based authentication is implemented to ensure secure handling of sensitive user information.

## Technologies Used

    Node.js: Server-side JavaScript runtime.
    MongoDB: NoSQL database for storing user information.
    JWT (JSON Web Token): Used for secure authentication.
    Postman: For testing API functionality

## Dependencies

### Main Dependencies

- `bcryptjs`: For hashing passwords.
- `config`: For managing environment variables.
- `express`: For setting up the web server and defining routes.
- `express-validator`: For validating request data.
- `gravatar`: For fetching user avatars.
- `jsonwebtoken`: For handling JWT-based authentication.
- `mongoose`: For interacting with MongoDB.

### Development Dependencies

- `concurrently`: For running multiple commands concurrently (useful in full-stack projects).
- `nodemon`: For automatically restarting the server when file changes are detected.
