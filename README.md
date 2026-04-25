# MERN Kanban Board – Task Management Web Application

A full-stack collaborative Kanban board built using the MERN stack (MongoDB, Express.js, React.js, Node.js).
This web application allows multiple users to manage and track tasks across different stages such as **To Do**, **In Progress**, and **Done**.

---

## 🚀 Features

* Multi-user collaborative task management
* Task organization using Kanban workflow (To Do, In Progress, Done)
* RESTful API development using Node.js and Express
* MongoDB Atlas integration for shared data storage
* Real-time updates for seamless collaboration
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
* CORS
* Dotenv

---

## 📁 Project Structure

kanban-app/
│
├── server/
│   ├── client/
│   ├── routes/
│   ├── models/
│   ├── .env
│   ├── index.js
│   └── package.json

---

## ⚙️ Installation

### 1. Clone the repository

git clone <your-repo-link>
cd kanban-app/server

---

### 2. Install dependencies

npm install

---

### 3. Setup environment variables

Create a `.env` file inside the `server` folder:

PORT=8000
MONGO_URL=your_mongodb_connection_string

---

### 4. Run backend server

npm start

Backend runs on:
http://localhost:8000

---

### 5. Run frontend

cd client
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
* Implemented collaborative task management system
* Connected frontend and backend for real-time interaction

---

## 🙋‍♀️ Author

**Shivani Vishwakarma**

---

## 📄 License

This project is open source and available under the MIT License.
