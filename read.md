# Chaticus: Multi-Container Application

## 🧠 Objective

The goal of this assignment was to convert a basic chat app into a multi-container application using Docker Compose. I wanted to add proper separation between services (backend and database) and enhance the app structure with multi-table support.

---

## 🔨 What I Implemented

✅ Forked the original repository  
✅ Created a Dockerfile for the backend (Node.js + Express)  
✅ Set up a PostgreSQL container with initial SQL schema  
✅ Added two tables: `users` and `messages`  
✅ Configured environment variables for secure DB connection  
✅ Connected backend and database via Docker Compose

---

## 💡 Tech Stack Used

- **Node.js** – for backend logic  
- **Express.js** – server framework  
- **PostgreSQL** – relational database  
- **Docker** – containerization  
- **Docker Compose** – multi-container orchestration

---

## ▶️ How to Run

```bash
# Clone the repository
git clone <your-repo-link>

# Build and run the containers
docker-compose up --build
