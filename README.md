# 🗄️ MongoDB Database Application — SBA319

**Course Project** • Node.js, Express & MongoDB Fundamentals

This project is a backend server application built using **Node.js, Express, and MongoDB**. It demonstrates how to design and implement a **CRUD API** with persistent data storage, validation, and performance optimization using MongoDB indexes.

---

## 🎯 Project Objectives

- Create a server application with Node.js, Express, and MongoDB
- Build a RESTful CRUD API
- Connect an Express server to a MongoDB database
- Create and use MongoDB indexes for efficient queries
- Define MongoDB validation rules
- Ensure data consistency through schema validation

---

## 🧠 About the Project

This application expands on backend fundamentals by introducing **database integration**.  
It focuses on how servers interact with stored data and how to:

- Persist data beyond server runtime
- Perform Create, Read, Update, and Delete (CRUD) operations
- Optimize queries using indexing
- Enforce data integrity through validation rules

The project emphasizes backend logic and database design rather than frontend UI.

---

## 🛠️ Technologies Used

| Technology | Purpose |
|------------|---------|
| **Node.js** | JavaScript runtime |
| **Express.js** | Server framework |
| **MongoDB** | NoSQL database |
| **Mongoose (if used)** | Schema modeling and validation |
| **JavaScript** | Backend logic |

---

## 📁 Project Structure

├── server.js / app.js – Express server setup
├── routes/ – API route definitions
├── models/ – MongoDB schemas and validation
├── controllers/ – CRUD logic (if present)
├── config/ – Database connection setup
├── package.json – Dependencies and scripts
└── README.md – Documentation


---

## ⚙️ How It Works

1. The Express server initializes and connects to MongoDB
2. API routes handle CRUD operations:
   - Create new records
   - Retrieve existing data
   - Update stored documents
   - Delete records
3. MongoDB validation rules ensure data consistency
4. Indexes are applied to improve query performance
5. JSON responses are returned to the client

---

## ▶️ How to Run Locally

1. Clone the repository  
2. Install dependencies:
   ```bash
   npm install
3. Ensure MongoDB is running locally or update the connection string
4. Start the server:
    npm start
    or
    ```bash
    node server.js
5. Test API endpoints using a browser or tool like Postman:
    http://localhost:3000

🧩 Learning Outcomes

Through this project, I practiced:

✔ Designing RESTful APIs
✔ Integrating MongoDB with Express
✔ Implementing CRUD operations
✔ Using MongoDB indexes for performance
✔ Applying validation rules for data integrity
✔ Understanding backend data flow

📌 Notes

This project was completed as part of Software Bootcamp Assignment 319 (SBA319) and represents my continued growth in backend and database-driven development.

✨ Author

TeMecha Griffin (MsGem0523)
Aspiring Software Engineer | Backend-Focused Developer