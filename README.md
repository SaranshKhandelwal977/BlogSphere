# BlogSphere - Full Stack Blog Application (MERN)

Welcome to the repository for BlogSphere, a full-stack MERN (MongoDB, Express.js, React.js, Node.js) application designed for creating and managing blogs. This project includes features such as user authentication, blog creation, editing, deletion, and public viewing of posts. Users can view posts even without logging in.

## Table of Contents

- [1. Introduction](#1-introduction)
- [2. Project Functionalities](#2-project-functionalities)
- [3. Technologies Used](#3-technologies-used)
- [4. Installation](#4-installation)
- [5. Usage](#5-usage)
- [6. Live Demo](#6-live-demo)
- [7. Contributing](#7-contributing)

## 1. Introduction

The BlogSphere project is a full-stack blogging platform that allows users to create, manage, and view blog posts. Users can sign up or log in to create new blogs, edit existing ones, and delete their posts. Blogs are displayed on the homepage in a summarized format, and clicking on a blog shows the full post. Public users can view posts without logging in, and clicking on a username will display all posts by that user.

## 2. Project Functionalities

- **User Authentication:**

  - Users can sign up and log in using their username and email.
  - Users who log in can create, edit, and delete blog posts.

- **Blog Management:**

  - Authenticated users can create new blog posts.
  - Users can view all their blogs by visiting the "Your Posts" section.
  - Blog owners can edit or delete their own posts.

- **Public Blog Viewing:**

  - All blog posts are displayed on the homepage in a short format.
  - Clicking on a blog displays the full post.
  - Clicking on the username of a blog shows all posts by that user.

## 3. Technologies Used

The project is built using the following technologies:

- **Frontend**:
  - React.js: For building the user interface.
  - HTML and CSS: For structuring and styling the application.
- **Backend**:
  - Node.js: For server-side logic.
  - Express.js: As the web application framework.
  - MongoDB: For database management.
- **Authentication**:
  - JWT (JSON Web Tokens): For secure user authentication.
  - bcrypt.js: For password hashing and encryption.
- **HTTP Requests**:
  - Axios: For making HTTP requests between the frontend and backend.
- **Routing**:
  - React Router: For handling client-side routing.

## 4. Installation

To run the project locally, follow these steps:

1. Clone the repository:
```bash
git clone https://github.com/SaranshKhandelwal977/BlogSphere.git
```
2. Navigate to the project directory:
```bash
cd BlogSphere
```
3. Install the dependencies for both the frontend and backend:
```bash
npm install
cd backend
npm install
```
4. Set up your MongoDB database and update the connection string in the backend `.env` file.

5. Start the backend server:
```bash
npm start
```
6. Start the frontend development server:
```bash
cd ..
npm start
```
7. Open your browser and go to `http://localhost:3000` to access the application.

## 5. Usage

1. Sign up or log in to create a new blog post.
2. Navigate to the "Create Blog" section to write and publish a blog post.
3. Visit the "Your Posts" section to manage your blog posts (edit or delete).
4. Explore the homepage to view public blog posts.
5. Click on any username to view all posts by that user.

## 6. Live Demo

Check out the live demo of the BlogSphere [here]([https://study-notion-ed-tech-eight.vercel.app/](https://blog-sphere-steel.vercel.app/)).

## 7. Contributing

Contributions are welcome! If you find any issues or want to add new features, feel free to submit a pull request.
1. Fork the repository.
2. Create a new branch for your feature: `git checkout -b feature-name`.
3. Commit your changes: `git commit -m "Add feature-name"`.
4. Push to the branch: `git push origin feature-name`.
5. Submit a pull request.


