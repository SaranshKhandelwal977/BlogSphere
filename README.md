# BlogSphere - Full Stack Blog Application (MERN)
# 
# BlogSphere is a full-stack blog application where users can create, manage, and view blog posts. 
# Built using the **MERN** (MongoDB, Express.js, React.js, Node.js) stack, the application allows 
# users to sign up, log in, and perform CRUD (Create, Read, Update, Delete) operations on their blog posts.

# ================================
# Table of Contents
# ================================

# 1. Features
# 2. Technologies Used
# 3. Installation
# 4. Usage
# 5. Live Demo
# 6. Dependencies
# 7. Contributing
# 8. License

# ================================
# 1. Features
# ================================

# - User Authentication: Users can sign up and log in to create and manage their blog posts.
# - Create New Blog: Authenticated users can create new blog posts.
# - View All Blogs: Users can view all the blog posts on the homepage in a short summary format. 
#   Clicking on any blog post will open the full blog.
# - View All User Blogs: Clicking on the username on any blog will display all blog posts created 
#   by that specific user.
# - Manage Blogs: Authenticated users can edit or delete their own blog posts by visiting the 
#   "Your Posts" section.
# - Public Blog Viewing: Visitors can view blogs even if they are not logged in.

# ================================
# 2. Technologies Used
# ================================

# - Frontend: React.js, HTML, CSS, JavaScript
# - Backend: Node.js, Express.js
# - Database: MongoDB
# - Authentication: JSON Web Tokens (JWT) and bcrypt.js for password hashing
# - Routing: React Router for client-side navigation

# ================================
# 3. Installation
# ================================

# To set up and run this project locally, follow these steps:

# Step 1: Clone the repository:

git clone https://github.com/your-username/blogsphere.git

# Step 2: Navigate to the project directory:

cd blogsphere

# Step 3: Install backend dependencies:

cd server
npm install

# Step 4: Set up environment variables for the backend:
# Create a `.env` file in the `server` directory and add the following variables:

echo "MONGO_URI=<your_mongodb_connection_string>" > server/.env
echo "JWT_SECRET=<your_jwt_secret>" >> server/.env
echo "PORT=5000" >> server/.env

# Step 5: Start the backend server:

npm start

# Step 6: Install frontend dependencies:

cd ../client
npm install

# Step 7: Start the frontend development server:

npm start

# Step 8: Open your browser:

# Navigate to http://localhost:3000 to access the application.

# ================================
# 4. Usage
# ================================

# 1. Sign Up/Log In: Create a new account or log in with an existing account.
# 2. Create New Blog: After logging in, navigate to the "Create Blog" section to write and publish a new blog post.
# 3. View Blogs: Visit the homepage to see all the blogs displayed in a summarized format. Click on any blog post to read the full blog.
# 4. Manage Blogs: Go to the "Your Posts" section to view, edit, or delete your own blog posts.
# 5. View Other Users' Blogs: Click on any username in the blog to view all the posts created by that user.

# ================================
# 5. Live Demo
# ================================

# Check out the live demo of BlogSphere [here](https://your-live-demo-link.com).

# ================================
# 6. Dependencies
# ================================

# Backend:
# - express
# - mongoose
# - bcryptjs
# - jsonwebtoken
# - cors

# Frontend:
# - react
# - react-dom
# - axios
# - react-router-dom

# ================================
# 7. Contributing
# ================================

# Contributions are welcome! If you would like to contribute to this project, please follow these steps:

# Step 1: Fork the repository.

# Step 2: Create a new branch for your feature:

git checkout -b feature-name

# Step 3: Commit your changes:

git commit -m "Add feature-name"

# Step 4: Push to the branch:

git push origin feature-name

# Step 5: Submit a pull request.

# ================================
# 8. License
# ================================

# This project is licensed under the MIT License.
