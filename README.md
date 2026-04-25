# DevOps Web Application 🚀

This project is a simple DevOps-based web application using Docker and Docker Compose. It demonstrates containerization, multi-service setup, and basic infrastructure management.

---

## 📦 Project Overview

This project consists of:

- 🌐 **rontend Web Server** using Nginx
- 🗄️ **Database** using MySQL
- 🐳 **Docker & Docker Compose** for container orchestration

---

## 🛠️ Technologies Used

- Docker
- Docker Compose
- Nginx
- MySQL
- HTML / CSS

---

## 📂 Project Structure

project-root/
│
├── app/
│ ├── Dockerfile
│ └── index.html
│
├── docker-compose.yml
└── README.md


---

## ⚙️ How It Works

### 🔹 Web Service
- Built using Nginx
- Serves a static HTML page
- Runs on port `80` inside container

### 🔹 Database Service
- Uses MySQL image
- Stores data using Docker volume
- Environment variables configure DB

---

## 🚀 Running the Project

### 1️⃣ Build and start containers

- docker compose up -d

## Access the application

- http://localhost:8086

## Stop the container

- docker compose down

---

## 📊 Features

- Multi-container setup (Web + DB)
- Persistent storage using volumes
- Custom Dockerfile for Nginx
- Simple responsive UI
- DevOps project structure

---

## 🧠 What I Learned

- Docker image creation and containerization
- Docker Compose for multi-service applications
- Port mapping and networking
- Volume management for data persistence
- Basic DevOps workflow
