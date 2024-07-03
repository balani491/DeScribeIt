# DeScribeIt - A CRUD Blogging Platform

![DeScribeIt Logo](https://via.placeholder.com/150)

Welcome to DeScribeIt, a full-stack blogging platform that allows users to create, read, update, and delete blog posts. The platform includes user authentication with JWT, allowing for secure login and signup processes.

Hosted at: [DeScribeIt](https://describeit.netlify.app/)

## Table of Contents
- [Features](#features)
- [Technology Stack](#technology-stack)
- [Installation](#installation)
- [Configuration](#configuration)
- [Usage](#usage)
- [API Endpoints](#api-endpoints)
- [Folder Structure](#folder-structure)
- [Screenshots](#screenshots)
- [Contributing](#contributing)
- [License](#license)
- [Contact](#contact)

## Features
- User registration and authentication with JWT
- Create, read, update, and delete blog posts
- Responsive design with a user-friendly interface
- Secure API endpoints using Express and JWT
- Backend built with Node.js, Express, and MongoDB
- Frontend built with React and TypeScript
- Real-time updates with a RESTful API

## Technology Stack
- **Frontend**: React, TypeScript, CSS, HTML
- **Backend**: Node.js, Express, TypeScript
- **Database**: MongoDB
- **Authentication**: JSON Web Tokens (JWT)
- **Hosting**: Netlify

## Installation

### Prerequisites
- Node.js (v14 or higher)
- MongoDB

### Steps
1. **Clone the repository:**
   ```bash
   git clone https://github.com/balani491/DeScribeIt.git
   cd DeScribeIt
Install backend dependencies:

bash
Copy code
cd backend
npm install
Install frontend dependencies:

bash
Copy code
cd ../frontend
npm install
Configuration
Backend
Create a .env file in the backend directory and add the following environment variables:

env
Copy code
PORT=5000
MONGODB_URI=your_mongodb_uri
JWT_SECRET=your_jwt_secret
Start the backend server:

bash
Copy code
npm run dev
Frontend
Create a .env file in the frontend directory and add the following environment variables:

env
Copy code
REACT_APP_API_URL=http://localhost:5000
Start the frontend server:

bash
Copy code
npm start
Usage
Running the Application Locally
Ensure MongoDB is running.
Start the backend server (see above).
Start the frontend server (see above).
Open your browser and navigate to:
bash
Copy code
http://localhost:3000
Creating a New User
Navigate to the sign-up page.
Fill in the registration form.
Submit the form to create a new account.
Creating a Blog Post
Log in to your account.
Navigate to the "Create Post" page.
Fill in the blog post details and submit.
Viewing and Managing Posts
Log in to your account.
Navigate to the "My Posts" page to view and manage your posts.
API Endpoints
User Routes
POST /api/auth/signup - Register a new user.
POST /api/auth/login - Log in an existing user.
GET /api/auth/logout - Log out the current user.
Blog Routes
GET /api/posts - Retrieve all posts.
GET /api/posts/:id - Retrieve a specific post.
POST /api/posts - Create a new post.
PUT /api/posts/:id - Update a post.
DELETE /api/posts/:id - Delete a post.
Folder Structure
bash
Copy code
DeScribeIt/
│
├── backend/
│   ├── src/
│   │   ├── controllers/
│   │   ├── models/
│   │   ├── routes/
│   │   ├── services/
│   │   ├── utils/
│   ├── .env
│   ├── package.json
│   └── tsconfig.json
│
├── frontend/
│   ├── src/
│   │   ├── components/
│   │   ├── pages/
│   │   ├── services/
│   │   ├── styles/
│   ├── .env
│   ├── package.json
│   └── tsconfig.json
│
└── README.md
Screenshots

Home Page


Blog Post


Login Page

Contributing
Fork the repository.
Create a new branch for your feature or bug fix:
bash
Copy code
git checkout -b feature-name
Commit your changes:
bash
Copy code
git commit -m "Describe your feature"
Push to the branch:
bash
Copy code
git push origin feature-name
Create a pull request.
License
This project is licensed under the MIT License. See the LICENSE file for details.

Contact
For any inquiries, feel free to contact us at: support@describeit.netlify.app.
