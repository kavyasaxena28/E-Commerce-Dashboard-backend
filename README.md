# 🛒 E-Commerce Dashboard Backend

A RESTful backend API for an E-Commerce Dashboard built using **Node.js**, **Express.js**, and **MongoDB Atlas**. This backend provides secure user authentication and complete CRUD operations for product management.

## 🚀 Live API

https://e-commerce-dashboard-backend-8bhd.onrender.com

## 🌐 Frontend Repository

https://github.com/kavyasaxena28/E-Commerce-Dashboard-frontend

## 🌍 Live Frontend

https://e-dashboardfrontend.netlify.app/

---

## ✨ Features

- 🔐 User Registration
- 🔑 User Login with JWT Authentication
- 📦 Add Products
- 📋 View All Products
- ✏️ Update Product Details
- 🗑️ Delete Products
- 🔍 Search Products
- ☁️ MongoDB Atlas Integration
- 🌐 RESTful API Architecture
- 🚀 Deployed on Render

---

## 🛠️ Tech Stack

- Node.js
- Express.js
- MongoDB Atlas
- Mongoose
- JWT (jsonwebtoken)
- CORS

---

## 📁 Project Structure

```
db/
├── config.js
├── Product.js
├── User.js

index.js
package.json
```

---

## 📌 API Endpoints

| Method | Endpoint | Description |
|--------|----------|-------------|
| POST | `/register` | Register a new user |
| POST | `/login` | Login user |
| POST | `/add-product` | Add a new product |
| GET | `/products` | Get all products |
| GET | `/product/:id` | Get a single product |
| PUT | `/product/:id` | Update product |
| DELETE | `/product/:id` | Delete product |
| GET | `/search/:key` | Search products |

---

## ⚙️ Installation

Clone the repository

```bash
git clone https://github.com/kavyasaxena28/E-Commerce-Dashboard-backend.git
```

Go to the project directory

```bash
cd E-Commerce-Dashboard-backend
```

Install dependencies

```bash
npm install
```

Create a `.env` file (recommended) and add your MongoDB connection string.

Start the server

```bash
npm start
```

For development

```bash
npm run dev
```

---

## 📸 API Testing

You can test the APIs using:

- Postman
- Thunder Client
- Insomnia

---

## 🔮 Future Enhancements

- Product Image Upload
- JWT Route Protection Middleware
- User Roles (Admin/User)
- Pagination
- Input Validation
- Better Error Handling
- Environment Variable Configuration

---

## 👩‍💻 Author

**Kavya Saxena**

GitHub: https://github.com/kavyasaxena28

LinkedIn: https://www.linkedin.com/in/kavya-saxena-13361b2b8

---

⭐ If you found this project useful, don't forget to **Star** the repository.
