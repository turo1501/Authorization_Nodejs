# Node.js JWT Authentication Project

![Node.js](https://img.shields.io/badge/Node.js-v20.15.1-green)
![Express](https://img.shields.io/badge/Express-v4.21.2-blue)
![JWT](https://img.shields.io/badge/JWT-v9.0.2-red)
![License](https://img.shields.io/badge/License-ISC-yellow)

A simple Node.js application demonstrating JWT (JSON Web Token) authentication. This project includes user login, token generation, and protected routes that require a valid JWT for access.

## Table of Contents

- [Features](#features)
- [Prerequisites](#prerequisites)
- [Installation](#installation)
- [Usage](#usage)
- [API Endpoints](#api-endpoints)
- [Environment Variables](#environment-variables)
- [Contributing](#contributing)
- [License](#license)

## Features

- **User Login**: Authenticate users by checking username and password.
- **JWT Generation**: Generate a JSON Web Token (JWT) upon successful login.
- **Protected Routes**: Access to the dashboard is restricted to requests with a valid JWT.
- **Error Handling**: Custom error handling for invalid requests and server errors.
- **Frontend Integration**: Simple HTML frontend to interact with the API.

## Prerequisites

Before you begin, ensure you have the following installed:

- [Node.js](https://nodejs.org/) (v20.15.1 or higher)
- [npm](https://www.npmjs.com/) (usually comes with Node.js)

## Installation

1. **Clone the repository:**

   ```bash
   git clone https://github.com/turo1501/Authorization_Nodejs.git
   cd nodejs-jwt
Install dependencies:

bash
Copy
npm install
Set up environment variables:

Create a .env file in the root directory and add the following:

env
Copy
JWT_SECRET=your_jwt_secret_key
PORT=3000
Replace your_jwt_secret_key with a secure secret key for JWT signing.

Start the application:

bash
Copy
npm start
The application will start and listen on port 3000 (or the port specified in .env).