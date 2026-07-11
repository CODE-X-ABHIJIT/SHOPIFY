# 🛍️ SHOPIFY - E-Commerce Web Application

<p align="center">
  <img src="https://img.shields.io/badge/Node.js-Express-339933?style=for-the-badge&logo=node.js">
  <img src="https://img.shields.io/badge/Express.js-Framework-black?style=for-the-badge&logo=express">
  <img src="https://img.shields.io/badge/MongoDB-Database-47A248?style=for-the-badge&logo=mongodb">
  <img src="https://img.shields.io/badge/Mongoose-ODM-880000?style=for-the-badge">
  <img src="https://img.shields.io/badge/EJS-Templates-B4CA65?style=for-the-badge">
  <img src="https://img.shields.io/badge/Tailwind_CSS-UI-06B6D4?style=for-the-badge&logo=tailwindcss">
</p>

---

# 📖 Overview

**SHOPIFY** is a full-stack e-commerce web application built with **Node.js**, **Express.js**, **MongoDB**, and **EJS**. It provides a complete shopping experience with secure user authentication, product browsing, shopping cart management, and an administrative interface for managing products.

The application follows the **MVC (Model-View-Controller)** architecture, ensuring clean separation of concerns and maintainable code.

live at: https://shopify-responsive-2m5s.onrender.com/

---

# ✨ Features

## 🔐 User Authentication

* User Registration
* Secure Login & Logout
* JWT-based Authentication
* Password Hashing
* Protected Routes
* Forgot Password via Email

---

## 👤 User Dashboard

* User Account Page
* Profile Management
* Personalized Shopping Experience

---

## 🛍️ Product Management

* Browse Products
* Product Details Page
* Search & Explore Products
* Product Images
* Product Pricing

---

## 🛒 Shopping Cart

* Add Products to Cart
* View Cart
* Manage Cart Items
* Checkout Preparation

---

## 👨‍💼 Admin Panel

* Admin Registration
* Admin Login
* Create Products
* Edit Products
* Product Management Dashboard

---

## 📧 Email Integration

* Password Reset Emails
* Nodemailer Configuration

---

# 🏗️ System Architecture

```text
                Client (Browser)
                       │
                       ▼
                Express.js Server
                       │
        ┌──────────────┼──────────────┐
        ▼              ▼              ▼
 Authentication   Product Module   Cart Module
        │              │              │
        └──────────────┼──────────────┘
                       ▼
                  MongoDB Database
```

---

# 🛠️ Tech Stack

## Backend

* Node.js
* Express.js
* MongoDB
* Mongoose
* JWT (JSON Web Token)
* bcrypt
* Multer
* Nodemailer

## Frontend

* EJS
* HTML5
* CSS3
* Tailwind CSS
* JavaScript

## Database

* MongoDB

---

# 📂 Project Structure

```text
SHOPIFY
│
├── config
│   ├── keys.js
│   ├── mongoose-connection.js
│   └── multer-config.js
│
├── controllers
│   └── authController.js
│
├── middlewares
│   ├── auth.js
│   └── isLoggedIn.js
│
├── models
│   ├── user-model.js
│   ├── owners-model.js
│   └── product-model.js
│
├── routes
│   ├── index.js
│   ├── usersRouter.js
│   ├── ownersRouter.js
│   └── productsRouter.js
│
├── utils
│   ├── generateToken.js
│   └── nodemailer.js
│
├── public
│   ├── images
│   ├── javascripts
│   └── stylesheets
│
├── views
│   ├── index.ejs
│   ├── dashboard.ejs
│   ├── shop.ejs
│   ├── product-detail.ejs
│   ├── cart.ejs
│   ├── account.ejs
│   ├── admin.ejs
│   ├── createproducts.ejs
│   ├── editProduct.ejs
│   ├── forgot-password.ejs
│   └── partials
│
├── app.js
└── package.json
```

---

# 🚀 Application Workflow

```text
User Registration/Login
          │
          ▼
     JWT Generated
          │
          ▼
 Browse Products
          │
          ▼
 View Product Details
          │
          ▼
 Add to Cart
          │
          ▼
 View Shopping Cart
```

For administrators:

```text
Admin Login
      │
      ▼
Admin Dashboard
      │
      ▼
Create Product
      │
      ▼
Edit Product
      │
      ▼
Manage Product Catalog
```

---

# 🔒 Authentication

The application uses JWT for authentication.

Features include:

* Secure Login
* Protected Routes
* Authentication Middleware
* Password Encryption using bcrypt
* Password Reset Support

---

# 🚀 Getting Started

## Clone the Repository

```bash
git clone https://github.com/CODE-X-ABHIJIT/SHOPIFY.git

cd SHOPIFY/shopify
```

---

## Install Dependencies

```bash
npm install
```

---

## Configure Environment

Update the MongoDB connection and application secrets in the configuration files.

Example configuration:

```javascript
MONGODB_URI=<your_mongodb_connection_string>
JWT_SECRET=<your_secret_key>
EMAIL_USER=<your_email>
EMAIL_PASSWORD=<your_email_password>
```

---

## Start the Application

```bash
npm start
```

or

```bash
node app.js
```

The application will be available at:

```text
http://localhost:3000
```

---

# 📁 Major Views

The application includes the following pages:

* Home
* Shop
* Product Details
* Shopping Cart
* User Dashboard
* Account
* Login
* Forgot Password
* Admin Dashboard
* Create Product
* Edit Product

---

# 📊 Core Modules

* User Authentication
* Product Management
* Shopping Cart
* Admin Panel
* Email Notifications
* JWT Security
* File Upload Support

---

# 📸 Screenshots

Add screenshots for:

* Home Page
* Shop
* Product Details
* Shopping Cart
* User Dashboard
* Admin Dashboard
* Product Management
* Login
* Forgot Password

---

# 🚀 Future Enhancements

* Online Payment Gateway
* Wishlist
* Order History
* Product Reviews & Ratings
* Product Search & Filters
* Coupon & Discount System
* Inventory Management
* Order Tracking
* Role-Based Access Control
* Docker Deployment
* CI/CD Pipeline
* Cloud Deployment

---

# 🤝 Contributing

Contributions are welcome.

1. Fork the repository.
2. Create a feature branch.

```bash
git checkout -b feature-name
```

3. Commit your changes.

```bash
git commit -m "Add new feature"
```

4. Push the branch.

```bash
git push origin feature-name
```

5. Create a Pull Request.

---

# 📜 License

This project is intended for educational and portfolio purposes.

---

# 👨‍💻 Author

**Abhijit Sahu**

* GitHub: https://github.com/CODE-X-ABHIJIT

---

# ⭐ Support

If you found this project useful, consider giving it a **Star ⭐** on GitHub.
