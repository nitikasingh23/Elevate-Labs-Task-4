# Elevate-Labs-Task-4

# 🔗 Flask REST API - User Management

## 📌 Objective
This project is a simple REST API built using Flask to manage user data with basic CRUD operations.

---

## 🛠 Tools & Technologies
- Python
- Flask
- Postman / Curl

---

## ⚙️ Features
- GET all users
- GET single user
- POST (create user)
- PUT (update user)
- DELETE (remove user)

---

## 📁 Project Structure
- app.py → Flask application
- README.md → Documentation

---

## 🚀 How It Works

1. Flask is used to create API endpoints.
2. User data is stored in an in-memory list (temporary storage).
3. Each user has:
   - id
   - name
   - email
4. CRUD operations are implemented using different HTTP methods.

---

## 📡 API Endpoints

### 1. Get all users
GET /users

### 2. Get single user
GET /users/<id>

### 3. Create user
POST /users
Body (JSON):
{
  "name": "John",
  "email": "john@example.com"
}

### 4. Update user
PUT /users/<id>

### 5. Delete user
DELETE /users/<id>

---

## ▶️ How to Run

### Install Flask
pip install flask

### Run the app
python app.py

### Test API
Use Postman or curl:
curl http://127.0.0.1:5000/users

---

## 📌 Notes
- Data is not stored permanently (resets when server stops)
- This project is for learning REST API basics
