# Node.js Signup & Signin API

A simple **Node.js and Express** backend for user authentication with **signup** and **signin** functionality using **JWT** tokens and **bcrypt** for password hashing. Users are stored **in memory** for demo purposes.  

---

## Features

- User **signup** with password hashing (bcrypt).  
- User **signin** with JWT token generation.  
- Simple **test route** to verify server is running.  
- Uses **environment variables** for port and JWT secret.  

---

## Tech Stack

- Node.js  
- Express.js  
- bcryptjs (password hashing)  
- jsonwebtoken (JWT token generation)  
- dotenv (environment variables)  
- body-parser (parsing JSON requests)  

---

## Installation

1. **Clone the repository**

```bash
git clone [<your-repo-url>](https://github.com/ganeshavireddy/Singin-Singup-Using-Node-Express.js.git)]
cd backend


# Navigate to your project backend folder
cd backend

# Initialize npm (if you haven't already)
npm init -y

# Install required dependencies
npm install express body-parser bcryptjs jsonwebtoken dotenv

# Install nodemon as a dev dependency (optional, for auto-reload)
npm install --save-dev nodemon
# Using node
node server.js

# Or using nodemon for auto-reload
npx nodemon server.js
