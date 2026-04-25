# MERN Kanban Board – Task Management Web Application

A full-stack collaborative Kanban board built using the MERN stack (MongoDB, Express.js, React.js, Node.js).
This web application allows multiple users to manage and track tasks across different stages such as **To Do**, **In Progress**, and **Done** with real-time updates.

---

## 🚀 Features

* Multi-user collaborative task management
* Task organization using Kanban workflow (To Do, In Progress, Done)
* RESTful API development using Node.js and Express
* MongoDB Atlas integration for shared data storage
* Real-time updates using Socket.io (no page reload required)
* Frontend-backend communication using Axios

---

## 🛠 Tech Stack

### Frontend

* React.js
* Axios
* CSS

### Backend

* Node.js
* Express.js
* MongoDB Atlas
* Mongoose
* Socket.io
* CORS
* Dotenv

---

## 📁 Project Structure

kanban-app/
│
├── server/
│   ├── routes/
│   ├── models/
│   ├── .env
│   ├── index.js
│   └── package.json
│
├── client/
│   ├── src/
│   ├── public/
│   └── package.json

---

## ⚙️ Installation

### 1. Clone the repository

git clone <your-repo-link>
cd kanban-app

---

### 2. Setup Backend

cd server
npm install

Create a `.env` file:

PORT=8000
MONGO_URL=your_mongodb_connection_string

Start backend:

npm start

---

### 3. Setup Frontend

cd ../client
npm install
npm start

Frontend runs on:
http://localhost:3000

---

## 📌 API Test

GET http://localhost:8000/

Response:
API is running...

---

## 📚 Learning Outcomes

* Built a full-stack MERN web application
* Designed REST APIs and integrated MongoDB Atlas
* Implemented real-time updates using Socket.io
* Developed a collaborative task management system

---

## 🙋‍♀️ Author

**Shivani Vishwakarma**

---

## 📄 License

This project is open source and available under the MIT License.
