# DeScribeIt - A CRUD Blogging Platform

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
2. **Install Dependencies:**
    - Navigate to the frontend and install dependencies:
        ```sh
        cd frontend
        npm install
        ```
    - Navigate to the backend and install dependencies:
        ```sh
        cd backend
        npm install
        ```

3. **Environment Variables:**
    - Create a `.env` file in the backend directory and configure your MongoDB URI, JWT secret, and other necessary environment variables.
	 Example `.env` file:
	```sh
	PORT1=3000
    DATABASE_URL={YOUR_MONGO_DB_CONNECTION_STRING}
    JWT_SECRET = {YOUR_JWT_SECRET}

	```

4. **Run the Application:**
    - Start the backend server:
        ```sh
        cd backend
        tsc -b
        node src/index.js
        ```
    - Start the frontend development server:
        ```sh
        cd frontend
        npm run dev
        ```

   ## Usage

   1. **Access the Website**: Visit [DeScribeIt](https://describeit.netlify.app/).
      
   2. **Create a New Description**:
      - Click on the "New Description" button.
      - Fill in the required details for your content description.

   3. **Save and Preview**:
      - Save your description to see a real-time preview.
      
   4. **Export or Share**:
      - Export the description or share it using the provided options.


