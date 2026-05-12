# 🚗 ParkEasy - DevOps Enabled MERN Parking Management System

![CI](https://github.com/anikket7/DevOps-project/actions/workflows/ci.yml/badge.svg)

A modern full-stack parking management application built using the MERN stack
and enhanced with DevOps practices including Docker, Docker Compose,
GitHub Actions CI/CD, Render deployment, Vercel hosting, and MongoDB Atlas
cloud database integration.

---

## 🌐 Live Deployment

## Frontend (Vercel)

<https://your-vercel-url.vercel.app>

## Backend API (Render)

<https://parkeasy-backend-s3zb.onrender.com>

---

## 🔗 GitHub Repository

<https://github.com/anikket7/DevOps-project>

---

## ✨ Features

- 🔍 Search and book parking spots
- 🔐 JWT Authentication System
- 👁️ Password visibility toggle
- 👑 Admin dashboard for managing bookings and parking spots
- 🎟️ Automatic 5-digit parking entry code generation
- 📱 Fully responsive UI
- 🌙 Dark mode support
- 📜 Booking history management
- 🐳 Dockerized frontend and backend
- ⚙️ CI/CD pipeline using GitHub Actions
- 🗄️ MongoDB Atlas cloud database
- ☁️ Cloud deployment using Render & Vercel

---

## 🛠️ Tech Stack

## Frontend URL

- React.js
- Vite
- Tailwind CSS

## Backend URL

- Node.js
- Express.js

## Database

- MongoDB Atlas
- Mongoose

## DevOps Tools

- Docker
- Docker Compose
- GitHub Actions
- GitHub
- Docker Hub
- Render
- Vercel

---

## 🐳 Docker Hub Images

## Backend Image

<https://hub.docker.com/r/YOUR_USERNAME/parkeasy-backend>

## Frontend Image

<https://hub.docker.com/r/YOUR_USERNAME/parkeasy-frontend>

---

## 🏗️ System Architecture

```text
Developer
   ↓ Push Code
GitHub Repository
   ↓
GitHub Actions
   ↓
Docker Build & CI Pipeline
   ↓
Docker Hub
   ↓
Frontend (Vercel)
Backend API (Render)
   ↓
MongoDB Atlas
```

---

## ☁️ Cloud Deployment Architecture

```text
Frontend  → Vercel
Backend   → Render
Database  → MongoDB Atlas
CI/CD     → GitHub Actions
Containers → Docker
Source Code → GitHub
```

---

## ⚙️ CI/CD Workflow

```text
1. Developer pushes code to GitHub
2. GitHub Actions workflow triggers automatically
3. Docker images are built
4. Docker images are pushed to Docker Hub
5. Render deploys backend automatically
6. Vercel deploys frontend automatically
7. Updated application goes live
```

---

## 🚀 Local Development Setup

## 📋 Prerequisites

- Node.js v20+
- Docker Desktop
- Git

---

## 1️⃣ Clone Repository

```bash
git clone https://github.com/anikket7/DevOps-project.git
cd DevOps-project
```

---

## 2️⃣ Run Application Using Docker

```bash
docker compose up --build
```

---

## 🌱 Seed Database

Open a new terminal and run:

```bash
docker compose exec backend node seed.js
```

This creates:

- Admin account
- Initial database setup

---

## 🔑 Admin Credentials

```text
Email: admin@parkeasy.in
Password: admin@1234
```

---

## 🌐 Application URLs

## Frontend

```text
http://localhost:5173
```

## Backend

```text
http://localhost:5000
```

---

## 🐳 Docker Containers

This project uses 3 containers:

| Container | Purpose |
| --- | --- |
| Frontend | React Application |
| Backend | Express API Server |
| MongoDB | Database |

---

## 📂 Project Structure

```text
DevOps-project/
│
├── backend/
│   ├── models/
│   ├── routes/
│   ├── middleware/
│   ├── Dockerfile
│   └── server.js
│
├── frontend/
│   ├── src/
│   ├── public/
│   ├── Dockerfile
│   └── vite.config.js
│
├── .github/
│   └── workflows/
│       └── ci.yml
│
├── docker-compose.yml
├── README.md
└── .gitignore
```

---

## 🔐 API Endpoints

| Method | Endpoint | Description |
| --- | --- | --- |
| GET | /api/parking | Get all parking spots |
| POST | /api/auth/login | User login |
| POST | /api/auth/signup | User registration |
| POST | /api/parking/:id/book | Book parking spot |
| POST | /api/parking/:id/release | Release parking spot |
| GET | /api/user/profile | User profile |

---

## 📸 DevOps Features Implemented

- ✅ Docker Containerization
- ✅ Docker Compose Orchestration
- ✅ Multi-container Architecture
- ✅ MongoDB Atlas Integration
- ✅ CI/CD using GitHub Actions
- ✅ Automated Docker Builds
- ✅ MERN Stack Integration
- ✅ Cloud Deployment
- ✅ GitHub Repository Management
- ✅ Production Deployment Workflow

---

## 📊 Expected Results

- Successful CI/CD automation
- Dockerized application deployment
- Automated GitHub workflow execution
- Smooth frontend and backend integration
- Cloud database connectivity
- Fully functional parking management system
- Production-ready deployment architecture

---

## 📚 Learning Outcomes

- MERN Stack Application Deployment
- Docker Containerization
- Docker Compose Usage
- CI/CD Pipeline Automation
- GitHub Actions Workflow
- Cloud Deployment
- MongoDB Atlas Integration
- DevOps Workflow Implementation
- Version Control and Repository Management

---

## 👨‍💻 Author

### Aniket Kumar Singh

GitHub:
<https://github.com/anikket7>

---

## 📄 License

This project is created for academic DevOps CA-2 assessment purposes.
