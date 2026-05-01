🚀 Team Task Manager

A full-stack web application that helps teams manage projects, assign tasks, and track progress efficiently.

📌 Overview

Team Task Manager allows users to:

Create and manage projects
Add team members
Assign and track tasks
Monitor progress through a dashboard
🛠️ Tech Stack

Frontend

React (JavaScript)

Backend

Node.js
Express.js

Database

MongoDB Atlas

Authentication

JWT (JSON Web Tokens)
✨ Features
User authentication (Signup/Login)
Secure routes using JWT
Create and manage projects
Add/remove project members
Task management:
Create tasks
Assign tasks to users
Update task status
Delete tasks
Dashboard insights:
Total tasks
Tasks by status
Overdue tasks
Tasks per user
📁 Project Structure
server/   → Backend (Node.js + Express)
client/   → Frontend (React)
⚙️ Backend Setup
cd server
npm install
npm run dev

Create a .env file inside the server folder:

PORT=5000
MONGODB_URI=your_mongodb_connection_string
JWT_SECRET=your_secret_key
💻 Frontend Setup
cd client
npm install
npm start
🌐 API Base URL
http://localhost:5000/api
🔗 API Endpoints
🔐 Auth
POST /api/auth/signup
POST /api/auth/login
GET /api/auth/me
📁 Projects
POST /api/projects
GET /api/projects
GET /api/projects/:id
POST /api/projects/:id/members
DELETE /api/projects/:id/members/:userId
✅ Tasks
POST /api/tasks
GET /api/tasks/project/:projectId
PATCH /api/tasks/:taskId/status
DELETE /api/tasks/:taskId
📊 Dashboard
GET /api/dashboard/:projectId
🔄 How It Works
User signs up or logs in
JWT token is stored in localStorage
User creates a project
Admin adds members to the project
Tasks are created and assigned
Members can view and update tasks
Dashboard provides project insights
🚀 Deployment
Backend: Railway
Frontend: Railway / Netlify
Database: MongoDB Atlas
🎥 Demo

Add the following:

Live App URL
GitHub Repository Link
Demo Video
📬 Contributing

Feel free to fork this repository and submit pull requests.
