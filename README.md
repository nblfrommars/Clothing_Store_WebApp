# 🛒 E-Commerce Web Application

A full-stack e-commerce web application that allows users to browse products, manage shopping carts, and perform secure online payments via VNPay.

---

## 🚀 Features

* 🔐 User authentication & authorization (JWT-based)
* 🛍️ Product browsing and search
* 🛒 Shopping cart management
* 💳 Secure online payment integration with VNPay
* 👤 Role-based access control (Admin / User)
* 📦 Order management system
* ⭐ Product rating and review system
---

## 🧱 Tech Stack

### Frontend

* ReactJS
* Axios
* Bootstrap / CSS

### Backend

* Spring Boot
* Spring Security
* JWT (JSON Web Token)

### Database

* MySQL
* Spring Data JPA

### Payment Integration

* VNPay Gateway
* HMAC-SHA512 hashing for secure transactions

---

## ⚙️ System Architecture

The application follows a client-server architecture:

* Frontend (ReactJS) communicates with backend via RESTful APIs
* Backend (Spring Boot) handles business logic and authentication
* Database (MySQL) stores users, products, and orders

---

## 🔑 Key Highlights

* Designed and implemented secure authentication using JWT
* Integrated VNPay payment gateway with secure hashing
* Built RESTful APIs for scalable and maintainable backend services
* Structured relational database for efficient data management

---

## 📦 Installation & Setup
⚡ Quick Start (Recommended)

```Run the application locally using the provided script:

run.bat

//This will automatically start both the backend and frontend services.
```
🔧 Manual Setup
### Backend

```bash
cd backend
./mvnw spring-boot:run
```

### Frontend

```bash
cd frontend
npm install
npm start
```

## 👨‍💻 Author

**Bao Linh Nguyen**

* GitHub: https://github.com/nblfrommars

---

## 📌 Future Improvements

* Implement search optimization
* Deploy application to cloud (AWS / Docker)
* Developing personalized customer experiences
---
