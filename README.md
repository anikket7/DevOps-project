# 🚗 ParkEasy - DevOps Enabled MERN Parking Management System

A modern full-stack parking management application built using the MERN stack and enhanced with DevOps practices including Docker, Docker Compose, and GitHub Actions CI/CD pipeline automation.

---

# ✨ Features

- 🔍 Search and book parking spots
- 🔐 JWT Authentication System
- 👁️ Password visibility toggle
- 👑 Admin dashboard for managing bookings and parking spots
- 🎟️ Automatic 5-digit parking entry code generation
- 📱 Fully responsive UI
- 🌙 Dark mode support
- 🐳 Dockerized frontend and backend
- ⚙️ CI/CD pipeline using GitHub Actions
- 🗄️ MongoDB containerized database

---

# 🛠️ Tech Stack

## Frontend
- React.js
- Vite
- Tailwind CSS

## Backend
- Node.js
- Express.js

## Database
- MongoDB
- Mongoose

## DevOps Tools
- Docker
- Docker Compose
- GitHub Actions
- GitHub

---

# 🏗️ System Architecture

```text
Developer
   ↓ Push Code
GitHub Repository
   ↓
GitHub Actions
   ↓
Docker Compose Build
   ↓
Frontend Container
Backend Container
MongoDB Container
   ↓
Running Application
```

---

# 🚀 Local Development Setup

## 📋 Prerequisites

- Node.js v20+
- Docker Desktop
- Git

---

# 1️⃣ Clone Repository

```bash
git clone https://github.com/anikket7/DevOps-project.git
cd DevOps-project
```

---

# 2️⃣ Docker Setup (Recommended)

## Run Full Application Using Docker

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

# 🌐 Access Application

## Frontend

```text
http://localhost:5173
```

## Backend

```text
http://localhost:5000
```

---

# 🐳 Docker Containers

This project uses 3 containers:

| Container | Purpose |
|---|---|
| Frontend | React Application |
| Backend | Express API Server |
| MongoDB | Database |

---

# ⚙️ CI/CD Pipeline

This project uses GitHub Actions for Continuous Integration.

## Workflow

1. Developer pushes code to GitHub
2. GitHub Actions workflow triggers automatically
3. Docker containers are built
4. Application becomes deployment-ready

---

# 📂 Project Structure

```text
DevOps-project/
│
├── backend/
│   ├── Dockerfile
│
├── frontend/
│   ├── Dockerfile
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

# 🔐 API Endpoints

| Method | Endpoint | Description |
|---|---|---|
| GET | /api/parking | Get all parking spots |
| POST | /api/auth/login | User login |
| POST | /api/auth/signup | User registration |
| POST | /api/parking/:id/book | Book parking spot |

---

# 📸 DevOps Features Implemented

- ✅ Docker Containerization
- ✅ Docker Compose Orchestration
- ✅ Multi-container Architecture
- ✅ MongoDB Container
- ✅ CI/CD using GitHub Actions
- ✅ Automated Docker Builds
- ✅ MERN Stack Integration

---

# 👨‍💻 Author

## Aniket Kumar Singh

GitHub:
https://github.com/anikket7

---

# 📄 License

This project is created for academic DevOps CA-2 assessment purposes.