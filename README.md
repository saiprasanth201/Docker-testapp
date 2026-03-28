# Docker-testapp

## 📌 Overview

This project is a backend application built using Node.js and MongoDB, fully containerized using Docker and Docker Compose.

It demonstrates how to build, run, and manage multi-container applications using Docker.

---

## 🛠️ Tech Stack

* Node.js (Express)
* MongoDB
* Docker
* Docker Compose

---

## ⚙️ Features

* Add users via API
* Fetch users from database
* Mongo Express UI for database management
* Persistent storage using Docker volumes
* Multi-container architecture

---

## 🐳 Docker Setup

### 1. Clone the repository

```bash
git clone <your-repo-link>
cd <repo-name>
```

### 2. Run the application

```bash
docker compose -f mongodb.yaml up -d
```

---

## 🌐 Access the application

* Backend API:
  http://localhost:5050/getUsers

* Mongo Express:
  http://localhost:8081

---

## 🧠 What I Learned

* Docker containerization
* Docker Compose for multi-container apps
* Container networking (service names vs localhost)
* Debugging using Docker logs
* Image building and pushing to Docker Hub
* Volume management for persistent data

---

## 🚀 Future Improvements

* Add React frontend (Full MERN stack)
* Deploy on cloud (AWS / Render)
* Add authentication system

---

## 👨‍💻 Author

Sai Prasanth
