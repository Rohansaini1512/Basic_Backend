# Basic Authentication Backend

This repository contains the backend code for a basic authentication system. The backend is built using Node.js, Express, and MongoDB with Mongoose for data modeling. It includes user signup, signin, logout, and user information retrieval functionalities, secured with JWT for authentication.

## Features

- User registration (signup)
- User login (signin)
- User logout
- Retrieve user information
- JWT-based authentication

## Technologies Used

- Node.js
- Express.js
- MongoDB
- Mongoose
- JWT (JSON Web Token)
- Bcrypt.js

## Getting Started

### Prerequisites

- Node.js
- MongoDB

### Installation

1. Clone the repository:

    ```bash
    git clone https://github.com/Rohansaini1512/Basic_Backend.git
    cd Basic_Backend
    ```

2. Install dependencies:

    ```bash
    npm install
    ```

3. Create a `.env` file in the root directory and add the following environment variables:

    ```env
    PORT=5000
    MONGO_URI=your_mongodb_uri
    JWT_SECRET=your_jwt_secret
    ```

4. Start the server:

    ```bash
    npm start
    ```

    The server will start on `http://localhost:5000`.


### API Endpoints

#### Auth Routes

- `POST /api/auth/signup` - Register a new user
- `POST /api/auth/signin` - Authenticate a user and get a token
- `POST /api/auth/logout` - Logout a user
- `GET /api/auth/user` - Get user information (requires token)

### Sample .env File

```env
PORT=5000
MONGO_URI=your_mongodb_uri
JWT_SECRET=your_jwt_secret


