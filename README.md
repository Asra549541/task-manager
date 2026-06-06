# TaskFlow - Task Management App

A full-stack Task Management Web Application built with the MERN stack.

## Features
- User registration and login with JWT authentication
- Create, edit, delete, and view tasks
- Mark tasks as completed or pending
- Search and filter tasks
- Priority levels (High, Medium, Low)
- Secure password hashing with bcrypt
- Protected routes

## Tech Stack
- **Frontend:** React.js, Axios, React Router DOM
- **Backend:** Node.js, Express.js
- **Database:** MongoDB, Mongoose
- **Auth:** JWT, bcryptjs

## Setup Instructions

### Prerequisites
- Node.js installed
- MongoDB installed and running
- Git installed

### 1. Clone the repository
git clone https://github.com/YOUR_USERNAME/task-manager.git
cd task-manager

### 2. Setup Backend
cd backend
npm install

Create a .env file in the backend folder:
MONGO_URI=mongodb://localhost:27017/taskmanager
JWT_SECRET=mysecretkey123
PORT=5000

npm run dev

### 3. Setup Frontend
cd ../frontend
npm install
npm start

### 4. Open in browser
http://localhost:3000

## API Endpoints

### Auth
- POST /api/auth/register — Register new user
- POST /api/auth/login    — Login user

### Tasks (Protected)
- GET    /api/tasks      — Get all tasks
- POST   /api/tasks      — Create task
- PUT    /api/tasks/:id  — Update task
- DELETE /api/tasks/:id  — Delete task

## Screenshots
(Add your screenshots here)