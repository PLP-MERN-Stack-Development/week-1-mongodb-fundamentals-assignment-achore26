# 📚 MongoDB Fundamentals with Node.js

This project demonstrates how to set up a Node.js application that connects to MongoDB and performs various database operations using JavaScript.

## 📦 Prerequisites

Before getting started, ensure the following are installed on your machine:

- **[Node.js](https://nodejs.org/)** (v14 or higher recommended)
- **MongoDB**
  - Either installed and running locally (`mongodb://localhost:27017`)
  - Or use a **MongoDB Atlas** cloud database (requires free account)

---

## 🚀 Getting Started

### 1. Clone the Repository

```bash
git clone https://github.com/PLP-MERN-Stack-Development/week-1-mongodb-fundamentals-assignment-achore26.git
cd week-1-mongodb-fundamentals-assignment-achore26

2. Install Dependencies
bash
Copy code
npm install
⚙️ Configuration
Update the MongoDB connection string and database name inside db.js.

For local MongoDB:

js
Copy code
const uri = "mongodb://localhost:27017";
const dbName = "school";
For MongoDB Atlas, use the following pattern and replace placeholders:

js
Copy code
const uri = "mongodb+srv://<username>:<password>@cluster.mongodb.net/?retryWrites=true&w=majority";
const dbName = "school";


- [MongoDB Documentation](https://docs.mongodb.com/)
- [MongoDB University](https://university.mongodb.com/)
- [MongoDB Node.js Driver](https://mongodb.github.io/node-mongodb-native/) 
