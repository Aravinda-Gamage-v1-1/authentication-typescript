# Authentication System using Node.js, JWT, React, and TypeScript

This repository provides a secure authentication system using **Node.js**, **JSON Web Tokens (JWT)**, **React**, and **TypeScript**. It includes user registration, login, authentication middleware, and token-based authorization.

## Features
✅ User registration & login  
✅ Secure password hashing (bcrypt)  
✅ JWT-based authentication & authorization  
✅ Role-based access control  
✅ Token refresh mechanism  
✅ Fully typed with TypeScript  
✅ RESTful API with Express  
✅ Frontend authentication with React  

## Tech Stack
- **Backend:** Node.js, Express, JWT, bcrypt, TypeScript  
- **Frontend:** React, TypeScript, React Router, Context API  

## Installation & Setup

### 1. Clone the Repository
```sh
git clone https://github.com/your-username/authentication-system.git
cd authentication-system
```

### 2. Install Dependencies
```sh
# Install backend dependencies
cd backend
npm install

# Install frontend dependencies
cd ../frontend
npm install
```

### 3. Configure Environment Variables
Create a `.env` file in the backend directory and set up your environment variables:
```env
PORT=5000
JWT_SECRET=your_secret_key
DATABASE_URL=your_database_url
```

### 4. Run the Application
```sh
# Start the backend server
cd backend
npm run dev

# Start the frontend application
cd ../frontend
npm start
```

## API Endpoints
| Method | Endpoint        | Description          |
|--------|---------------|----------------------|
| POST   | /api/register | Register new user   |
| POST   | /api/login    | Authenticate user   |
| GET    | /api/user     | Get user profile (protected) |

## License
This project is licensed under the MIT License.

---


