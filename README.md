# fullstack-tasks-app

Complete MERN stack task management app.

Run backend and frontend as described in the project instructions.

## Register
![Register](frontend/public/Register.png)

## Login
![Login](frontend/public/Login.png)

## UserDashboard
![UserDashboard](frontend/public/UserDashboard.png)

## AdminPanel
![AdminPanel](frontend/public/AdminPanel.png)

## ViewTasks
![ViewTasks](frontend/public/ViewTasks.png)

## PromoteUser
![ViewTasks](frontend/public/PromoteUser.png)


# Fullstack Tasks App

A secure and scalable full-stack task management application with:

JWT authentication

Role-based access control

CRUD operations

Form validation

Security middlewares

API documentation

Request and error logging (Winston)

This project includes a backend REST API (Node.js + Express + MongoDB) and a React frontend to interact with the system.


# Tech Stack

## Backend

Node.js + Express

MongoDB + Mongoose

JWT Authentication + Bcrypt

Joi Request Validation

Winston Logger (combined.log, error.log)

Helmet, CORS, Rate Limiting, Sanitization

Swagger API Documentation


## Frontend

React (Vite)

Redux Toolkit

Axios (with interceptors)

TailwindCSS

Protected Routes & Auth State



# Getting Started — Run Locally

## 1️⃣ Clone the Repository
1) git clone https://github.com/Shivp45/FullStack_Tasks_Manager.git
2) cd fullstack-tasks-app

## 2️⃣ Backend Setup
1) cd backend
2) npm install

### Create .env inside /backend:

PORT=5000

MONGO_URI=your_mongodb_uri_here

JWT_SECRET=your_jwt_secret


NODE_ENV=development


### Start the backend server:
npm run dev

### If successful, you should see:
Server running on http://localhost:5000
Connected to MongoDB



### API Documentation

Once backend is running:

Swagger Docs → http://localhost:5000/api-docs
Health Check → http://localhost:5000/api/health



## 3️⃣ Frontend Setup
Open a second terminal:

1) cd frontend
2) npm install


### Run the frontend:
npm run dev

The frontend will start at:
http://localhost:5173/



## 4️⃣ Login & Testing

You can:

1) Register new users

2) Login

3) Create / update / delete tasks

4) Test protected routes

5) View admin-only functionality (if assigned role = admin)

