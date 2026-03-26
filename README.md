# 📚 Book Store Backend

This is the **backend API** for the Book Store Web App, built using **Node.js, Express, and MongoDB**.
It handles user authentication, book data management, and RESTful API services.

---

## 🚀 Live API

🔗 https://bookstore-backend-1-3nzk.onrender.com

---

## ✨ Features

* 🔐 User Authentication (Signup & Login)
* 🔑 Secure password hashing using bcryptjs
* 📖 Book data API
* 🌐 RESTful API architecture
* 💾 MongoDB Atlas cloud database integration
* ⚡ Fast and scalable backend

---

## 🛠️ Tech Stack

* Node.js
* Express.js
* MongoDB (Mongoose)
* bcryptjs
* CORS

---

## 📁 Project Structure

```bash
Backend/
│
├── controller/
│   ├── book.controller.js
│   └── user.controller.js
│
├── model/
│   ├── book.model.js
│   └── user.model.js
│
├── route/
│   ├── book.route.js
│   └── user.route.js
│
├── .env
├── index.js
├── package.json
└── package-lock.json
```

---

## ⚙️ Setup & Installation

### 1️⃣ Clone Repository

```bash
git clone https://github.com/nidhi-kumari10/bookstore-backend.git
cd bookstore-backend
```

---

### 2️⃣ Install Dependencies

```bash
npm install
```

---

### 3️⃣ Environment Variables

Create a `.env` file in the root directory:

```env
PORT=4001
MongoDBURI=your_mongodb_atlas_url
```

> Replace `your_mongodb_atlas_url` with your MongoDB Atlas connection string.

---

### 4️⃣ Run Server

```bash
nodemon index.js
```

---

## 🔗 API Endpoints

| Method | Endpoint     | Description         |
| ------ | ------------ | ------------------- |
| POST   | /user/signup | Register a new user |
| POST   | /user/login  | Authenticate user   |
| GET    | /book        | Fetch all books     |

---

## 🌐 API Base URL

```bash
https://bookstore-backend-1-3nzk.onrender.com
```

---

## 🚀 Deployment

* Hosted on **Render**
* Connected to GitHub repository
* Environment variables configured securely
* Auto deploy on push

---

## 📌 Notes

* Ensure MongoDB Atlas is properly connected
* Do not expose `.env` file publicly
* Fix typo if present:

  * `user.collroller.js` → `user.controller.js`

---

## 📖 Future Improvements

* 🔐 JWT Authentication
* 🛒 Cart & Order APIs
* ⭐ Reviews & Ratings system
* 📊 Admin dashboard

---

## 👨‍💻 Author

**Kumari Nidhi**
