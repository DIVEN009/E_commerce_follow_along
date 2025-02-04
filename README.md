# E_commerce_follow_along

# E-Commerce Backend (MERN Stack)

This is the backend for an e-commerce platform built with the MERN stack (MongoDB, Express, React, Node.js). It provides APIs for user authentication, product management, and order processing.

## Technologies

- *Node.js* & *Express* for building the server
- *MongoDB* for storing data
- *Mongoose* for MongoDB interactions
- *JWT* for user authentication
- *bcryptjs* for password hashing
- *dotenv* for environment variables

## Features

- User registration and login
- CRUD operations for products
- Order management

# Milestone #3
1) Backend folder structure
2) Create a structured hierarchy for organizing routes, controllers, models, and middleware.

# Server Setup

1) Use Node.js and Express to create a backend server.
2) Configure the server to listen on a designated port. Database Connection
3) Integrate MongoDB for efficient data storage.
4) Confirm the connection between the server and MongoDB.
5) Error Handling
6) Provide clear error messages for better debugging and user feedback.

1. Clone the repo:

   ```bash
   git clone https://github.com/ThakoorRishwanthKalvium/project_1.git

# Milestone 4

# User Management System  

## Overview  
This project involves creating a **User Model**, a **User Controller**, and setting up **Multer** for file uploads.  

## Features  
- User Model to define how user data is stored in MongoDB.  
- User Controller to handle requests related to user management.  
- File upload functionality using Multer.  

## 1. What’s a Model?  
A **model** is a blueprint that defines how data is structured in the database.  
- In MongoDB, we use **Schemas** to define the structure of a model.  
- The User Model includes fields like:  
  - `name` - User’s full name  
  - `email` - User’s email address  
  - `password` - User’s hashed password  
  - `profileImage` - Path to the uploaded profile picture  

## 2. What’s a Controller?  
A **controller** is responsible for handling user-related actions in the application.  
- It manages:  
  - **Creating users** (Sign-up)  
  - **Retrieving user data**  
  - **Updating user details**  
  - **Deleting user accounts**  

## 3. File Uploads with Multer  
To allow users to upload profile pictures, we use **Multer**.  
- Multer helps in storing user images securely.  
- Steps to configure Multer:  
  - Install Multer using `npm install multer`.  
  - Set up a middleware to handle file uploads.  
  - Store uploaded files in a specific directory (e.g., `uploads/`).  

## Steps for Milestone 4 📝  
This milestone includes:  
- [ ] Creating the **User Model**  
- [ ] Developing the **User Controller**  
- [ ] Setting up **Multer** for file uploads  
- [ ] Updating the **README.md** with progress  

## Installation  
1. Clone the repository:  
   ```bash
   git clone https://github.com/your-repo/user-management.git