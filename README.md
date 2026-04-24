# 🚀 Experiment 10 - CRUD Operations using Node.js & Express.js

## 📌 Project Overview

This project demonstrates how to perform **CRUD (Create, Read, Update, Delete)** operations using **Node.js**, **Express.js**, and **MongoDB**.
It includes REST APIs for managing student data and testing using Postman.

---

## 🎯 Objectives

* Build REST APIs using Node.js and Express.js
* Connect backend with MongoDB database
* Perform CRUD operations
* Understand routing and backend structure
* Test APIs using Postman

---

## 🧩 Features

* ➕ Create new student record
* 📄 Read all student records
* 🔍 Read single record by ID
* ✏️ Update existing record
* ❌ Delete record

---

## 💻 Tech Stack

* Node.js
* Express.js
* MongoDB
* Mongoose
* Postman

---

## 📁 Project Structure

```
experiment10/
│
├── server.js
├── models/
│   └── Student.js
├── routes/
│   └── studentRoutes.js
├── package.json
```

---

## ⚙️ Installation & Setup

### 1. Clone the repository

```
git clone https://github.com/prathana2003/experiment10.git
cd experiment10
```

### 2. Install dependencies

```
npm install
```

### 3. Start MongoDB

Make sure MongoDB is running on:

```
mongodb://127.0.0.1:27017
```

### 4. Run the server

```
npm start
```

Server will run on:

```
http://localhost:5000
```

---

## 🔗 API Endpoints

### 🔸 Create Record

* **POST** `/api/students`

**Body:**

```json
{
  "name": "Rahul",
  "email": "rahul@gmail.com",
  "course": "BCA"
}
```

---

### 🔸 Get All Records

* **GET** `/api/students`

---

### 🔸 Get Single Record

* **GET** `/api/students/:id`

---

### 🔸 Update Record

* **PUT** `/api/students/:id`

---

### 🔸 Delete Record

* **DELETE** `/api/students/:id`

---

## 🧪 Testing

All APIs were tested using **Postman**.

---

## 📸 Screenshots

* MongoDB Connected
* Create Record Success
* Read Records
* Update Record
* Delete Record
* MongoDB Compass View

---

## 📘 Conclusion

This project successfully demonstrates how to implement CRUD operations using Node.js, Express.js, and MongoDB. It provides a basic understanding of backend development and REST API handling.


