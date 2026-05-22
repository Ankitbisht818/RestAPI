# CRUD Post Application

A beginner-friendly CRUD application built using Node.js, Express.js, and EJS.

This project was created to understand the fundamentals of backend development and how CRUD operations work in a real application. Users can create posts, view posts, update existing posts, and delete posts using RESTful routes.

The application uses server-side rendering with EJS templates and follows the MVC-style routing structure commonly used in backend applications.

---

# Features

* Create new posts
* View all posts
* View individual posts
* Edit and update posts
* Delete posts
* Dynamic routing using route parameters
* RESTful routing structure
* Server-side rendering with EJS
* Unique ID generation using UUID
* Method Override for PATCH and DELETE requests
* Static file handling using Express

---

# Tech Stack

* Node.js
* Express.js
* EJS
* UUID
* Method-Override
* HTML
* CSS

---

# Project Structure

```bash id="ycdb56"
project-folder
│
├── public/
│   └── style.css
│
├── views/
│   ├── index.ejs
│   ├── new.ejs
│   ├── show.ejs
│   └── edit.ejs
│
├── node_modules/
├── package.json
├── package-lock.json
└── index.js
```

---

# Routes

| Method | Route           | Description                    |
| ------ | --------------- | ------------------------------ |
| GET    | /posts          | Display all posts              |
| GET    | /posts/new      | Show form to create a new post |
| POST   | /posts          | Create a new post              |
| GET    | /posts/:id      | Display a single post          |
| GET    | /posts/:id/edit | Show edit form                 |
| PATCH  | /posts/:id      | Update a post                  |
| DELETE | /posts/:id      | Delete a post                  |

---

# Concepts Learned

This project helped me understand:

* CRUD operations
* RESTful routing
* Express.js middleware
* Dynamic routes and route parameters
* Handling form data
* Server-side rendering using EJS
* Static file serving
* UUID generation
* Method Override
* Request and response handling
* Basic backend project structure

---

# Future Improvements

* Integrate SQL database for permanent data storage
* Connect MySQL or PostgreSQL
* Add authentication and authorization
* Improve frontend UI
* Add validations and error handling
* Build complete REST API support

---

# Author

Ankit Bisht
