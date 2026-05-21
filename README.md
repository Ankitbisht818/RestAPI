# CRUD Post Application

A simple and beginner-friendly CRUD application built using Node.js, Express.js, and EJS.

This project was created to understand the fundamentals of backend development and how CRUD operations work in a real application. Users can create posts, view all posts, and open individual posts using dynamic routing.

The application follows RESTful routing principles and uses server-side rendering with EJS templates.


# Features

* Create new posts
* View all posts
* View individual posts
* Dynamic routing using route parameters
* RESTful routing structure
* Server-side rendering with EJS
* Unique ID generation using UUID
* Static file handling using Express


# Tech Stack

* Node.js
* Express.js
* EJS
* UUID
* HTML
* CSS


# Project Structure

RestAPI
│
├── public/
│   └── style.css
│
├── views/
│   ├── index.ejs
│   ├── new.ejs
│   └── show.ejs
│
├── node_modules/
├── package.json
├── package-lock.json
└── index.js


# Routes

| Method | Route      | Description                |
| ------ | ---------- | -------------------------- |
| GET    | /posts     | Display all posts          |
| GET    | /posts/new | Show form to create a post |
| POST   | /posts     | Create a new post          |
| GET    | /posts/:id | Display a single post      |


# Concepts Learned

This project helped me understand:

* CRUD operations
* Express.js routing
* Middleware usage
* Dynamic routes and route parameters
* Handling form data
* Server-side rendering
* Static file serving
* RESTful APIs
* Project structure in Express applications


# Future Improvements

* Add update and delete functionality
* Connect MongoDB database
* Add authentication and authorization
* Improve frontend design
* Add validation and error handling
* Build REST API version


# Author

Ankit Bisht
