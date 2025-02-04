# 📨 Real-Time Messaging Application

This project consists of multiple services running in **Docker containers**, providing **real-time message handling** and **history retrieval**.

## 🚀 Services and Links

### 🔹 Backend with Swagger API Documentation (**backend-api**)
📌 [http://localhost:5241/swagger/index.html](http://localhost:5241/swagger/index.html)  
- Handles message processing and provides API endpoints.

### 🔹 Real-Time Message Display Client (**client-observer**)
📌 [http://localhost:5044/](http://localhost:5044/)  
- Displays messages in real-time using **WebSockets**.

### 🔹 Message History Viewer (**client-historian**)
📌 [http://localhost:5190/](http://localhost:5190/)  
- Allows users to select a time range and retrieve past messages.

### 🔹 Streaming Message Writer (**client-writer**)
- Implemented as a **background worker** without a UI.  
- Logs and status can be monitored via the **console**.

---

## 📥 Installation & Setup

### 1️⃣ Clone the Repository
```sh

2️⃣ Build and Run the Application with Docker
sh
docker-compose up --build
This will start all services within Docker containers.
