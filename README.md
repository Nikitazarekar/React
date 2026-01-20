# React

# 🎬 MERN Stack Movie Management System

A **Movie Management System** built using the **MERN Stack (MongoDB, Express.js, React.js, Node.js)**.
This application allows **cinema staff** to securely manage movie records including authentication, adding movies, viewing movies, and deleting movies.

---

## 📌 Problem Statement

Design and develop a Movie Management System using the MERN stack. The system is used by cinema staff to securely manage movie records stored in MongoDB and displayed on a React frontend.

---

## 🚀 Features

### 🔐 Staff Authentication

* Only **authorized staff** can log in
* Email & password validation
* Minimum **3 staff members** stored in the database

### 🎥 Movie Management

* Add new movie records
* Minimum **5 movies** stored in the database
* View all movies
* Fetch movie details from MongoDB
* Delete movie records (optional feature)

---

## 🛠️ Technology Stack

### Frontend

* React.js
* HTML5
* CSS3
* JavaScript (ES6)
* Axios

### Backend

* Node.js
* Express.js
* MongoDB (Community Server)
* Mongoose

---

## 📂 Project Structure

```
Movie-Management-System/
│
├── backend/
│   ├── models/
│   │   ├── Movie.js
│   │   └── Staff.js
│   ├── routes/
│   │   ├── authRoutes.js
│   │   └── movieRoutes.js
│   ├── controllers/
│   ├── config/
│   │   └── db.js
│   ├── server.js
│   └── package.json
│
├── frontend/
│   ├── src/
│   │   ├── components/
│   │   ├── pages/
│   │   ├── services/
│   │   └── App.js
│   └── package.json
│
└── README.md
```

---

## 🔑 Authentication Flow

1. Staff enters email and password
2. Backend validates credentials from MongoDB
3. On success, staff is allowed to access movie operations
4. Unauthorized users are blocked

---

## 📦 Database Collections

### Staff Collection

* name
* email
* password

### Movie Collection

* title
* genre
* duration
* language
* releaseDate

---

## ⚙️ Installation & Setup

### Prerequisites

* Node.js
* MongoDB Community Server
* MongoDB Shell (mongosh)

---

### Backend Setup

```bash
cd backend
npm install
npm start
```

### Frontend Setup

```bash
cd frontend
npm install
npm start
```

---

## 🔗 MongoDB Connection

```text
mongodb://localhost:27017/moviedb
```

---

## 🧪 Sample Login Credentials

| Email                                       | Password |
| ------------------------------------------- | -------- |
| [staff1@gmail.com](mailto:staff1@gmail.com) | 12345    |
| [staff2@gmail.com](mailto:staff2@gmail.com) | 12345    |
| [staff3@gmail.com](mailto:staff3@gmail.com) | 12345    |

---

## 🎯 Learning Outcomes

* Hands-on experience with MERN stack
* Understanding CRUD operations
* Authentication using MongoDB
* Frontend-backend integration

---
