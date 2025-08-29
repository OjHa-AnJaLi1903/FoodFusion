# 🍴 FoodFusion

A modern **full-stack food ordering web app** built with **React.js, Node.js, Express, and MongoDB**.  
The app provides a seamless experience to browse food items, manage cart, and place orders with **PayPal integration** for secure payments.

---

## 🚀 Features

- 📂 Browse food menu with images and details  
- 🛒 Add to Cart, Checkout & Track Orders  
- 👤 User Authentication (Login / Register)  
- 💳 PayPal Sandbox Integration for payments  
- 📱 Fully responsive design (mobile-friendly)  
- ⚡ Fast REST API with Express + MongoDB  
- 🌓 Dark Mode (optional if implemented)  

---

## 🛠️ Tech Stack

![React](https://img.shields.io/badge/React-20232A?style=for-the-badge&logo=react)
![Node.js](https://img.shields.io/badge/Node.js-339933?style=for-the-badge&logo=node.js)
![Express.js](https://img.shields.io/badge/Express.js-000000?style=for-the-badge&logo=express)
![MongoDB](https://img.shields.io/badge/MongoDB-4EA94B?style=for-the-badge&logo=mongodb)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript)
![npm](https://img.shields.io/badge/npm-CB3837?style=for-the-badge&logo=npm)

---

## 📦 Getting Started

### 1️⃣ Clone the Repository

```bash
git clone https://github.com/OjHa-AnJaLi1903/FoodFusion.git
cd FoodFusion
```

### 2️⃣ Install Dependencies

#### For client (frontend)
```bash
cd client
npm install
```

#### For server (backend)
```bash
cd ../server
npm install
```

### 3️⃣ Configure Environment Variables

Create a .env file inside the server/ folder:

PORT=5000
DATABASE_URL=your_mongodb_connection_string
JWT_SECRET=your_secret_key
PAYPAL_CLIENT_ID=your_paypal_client_id
DEPLOYMENT=http://localhost:3000

### 4️⃣ Run the App

#### Start Backend
```bash
cd server
npm start
```

#### Start Frontend
```bash
cd ../client
npm start
```

App will run at:

Backend 👉 http://localhost:5000

Frontend 👉 http://localhost:3000

---

## 🧪 Available Scripts
Command	Description
npm start	Starts dev server (frontend or backend)
npm run dev	Starts backend with Nodemon (if configured)
npm run build	Builds React app for production
npm test	Runs tests (if added)

---

## 📁 Folder Structure
FoodFusion/
├── client/ → React frontend
│ ├── src/
│ ├── public/
│ └── package.json
├── server/ → Node.js + Express backend
│ ├── db/
│ ├── models/
│ ├── routers/
│ ├── index.js
│ └── package.json
└── README.md

---

## ✍️ Author

**Anjali Ojha**  
_B.Tech CSE | Full Stack Developer (MERN)_
