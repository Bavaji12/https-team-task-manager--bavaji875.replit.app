# Team Task Manager 🚀

A full-stack Team Task Manager web application that helps teams create projects, assign tasks, track progress, and manage workflows efficiently using role-based access control.

## 🌐 Live Demo

[Live Application](https://team-task-manager--bavaji875.replit.app?utm_source=chatgpt.com)

---

# ✨ Features

* 🔐 User Authentication (Signup/Login)
* 👥 Role-Based Access (Admin / Member)
* 📁 Project Management
* ✅ Task Creation & Assignment
* 📊 Dashboard Analytics
* ⏰ Overdue Task Tracking
* 🔄 Task Status Updates
* 📱 Responsive UI
* 🌐 REST APIs
* 🗄️ MongoDB Integration

---

# 🛠️ Tech Stack

## Frontend

* React.js
* Tailwind CSS
* Axios
* React Router DOM

## Backend

* Node.js
* Express.js
* MongoDB
* Mongoose
* JWT Authentication
* bcryptjs

---

# 📂 Project Structure

```bash
team-task-manager/
│
├── frontend/
│   ├── src/
│   ├── public/
│   └── package.json
│
├── backend/
│   ├── models/
│   ├── routes/
│   ├── controllers/
│   ├── middleware/
│   └── server.js
│
└── README.md
```

---

# 🔑 Authentication

* JWT-based authentication
* Secure password hashing using bcryptjs
* Protected routes
* Role-based authorization

---

# 👨‍💻 User Roles

## Admin

* Create projects
* Assign team members
* Create and assign tasks
* Manage workflow

## Member

* View assigned tasks
* Update task status
* Track deadlines

---

# 📊 Dashboard Features

* Total Tasks
* Completed Tasks
* Pending Tasks
* Overdue Tasks

---

# ⚙️ Installation

## Clone Repository

```bash
git clone https://github.com/your-username/team-task-manager.git
```

---

# Backend Setup

```bash
cd backend
npm install
npm run dev
```

## Create `.env` file

```env
MONGO_URI=your_mongodb_connection
JWT_SECRET=your_secret_key
PORT=5000
```

---

# Frontend Setup

```bash
cd frontend
npm install
npm run dev
```

---

# 🚀 Deployment

## Backend

Deployed using Railway

[Railway](https://railway.app?utm_source=chatgpt.com)

## Frontend

Deployed using Replit / Vercel

[Vercel](https://vercel.com?utm_source=chatgpt.com)

---

# 📌 API Endpoints

## Authentication

* `POST /api/auth/signup`
* `POST /api/auth/login`

## Projects

* `GET /api/projects`
* `POST /api/projects`

## Tasks

* `GET /api/tasks`
* `POST /api/tasks`
* `PUT /api/tasks/:id`

---

# 📱 Responsive Design

* Mobile Friendly
* Tablet Responsive
* Desktop Optimized

---

# 🔮 Future Enhancements

* Real-time Notifications
* Team Chat
* File Uploads
* Calendar Integration
* Email Alerts
* Dark Mode

---

# 🎥 Demo Video

Include:

* Signup/Login
* Project Creation
* Task Assignment
* Dashboard Overview
* Status Updates
* Live Deployment

---

# 📄 License

This project is developed for educational and internship assessment purposes.

---

# ❤️ Developed By

Bavaji
Full Stack Developer | MERN Stack Enthusiast
