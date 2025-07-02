# 🧩 EJS-Express-MongoDB Backend Application

This is a backend web application built using **Express.js**, **MongoDB**, and **EJS** as the templating engine. The app includes user and post management with basic routing and database interactions.

## 🛠 Tech Stack

- **Node.js**
- **Express.js**
- **MongoDB + Mongoose**
- **EJS (Embedded JavaScript Templating)**
- **bcrypt (for password hashing)**
- **cookie-parser (for cookies and session handling)**
- **jsonwebtokens**

## 📁 Project Structure
project-root/
│
├── models/ # Mongoose schemas for User and Post
│ ├── user.js
│ └── post.js
│
├── views/ # EJS templates
│ ├── index.ejs
│ ├── login.ejs
│ ├── profil.ejs
│ └── edit.ejs
│
├── public/ # Static files (CSS, images, etc.)
│
├── app.js # Main application entry point
│
├── package.json
├── .gitignore
└── README.md # Project documentation


## 🚀 Features

- User registration and login
- Hashed passwords using bcrypt
- Session handling with cookies
- Create and view posts
- Rendered views using EJS


