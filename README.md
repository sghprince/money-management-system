# 💰 Money Management System

A full-stack **Money Management System** built using **Spring Boot (Backend)** and **React (Frontend)**.
This application helps users manage their income, expenses, and track financial activities efficiently.

---

## 🚀 Tech Stack

### 🔹 Backend

* Java
* Spring Boot
* Spring Security (JWT Authentication)
* Spring Data JPA (Hibernate)
* MySQL

### 🔹 Frontend

* React.js (Vite)
* HTML, CSS, JavaScript

### 🔹 Tools & Others

* Git & GitHub
* Postman (API Testing)
* Docker (Optional)

---

## ✨ Features

* 🔐 User Authentication (Login/Register using JWT)
* 💵 Add Income
* 💸 Track Expenses
* 📊 View Financial Summary
* 📧 Email Integration (for notifications)
* 🔒 Secure APIs with Spring Security

---

## 📁 Project Structure

```
MoneyManagementSystem/
│
├── backend/      # Spring Boot Application
├── fronted/      # React Application
├── README.md
└── .gitignore
```

---

## ⚙️ Setup Instructions

### 🔹 Backend Setup

1. Navigate to backend folder:

```
cd backend
```

2. Configure environment variables:

```
DB_USERNAME=your_db_username
DB_PASSWORD=your_db_password
MAIL_USERNAME=your_email
MAIL_PASSWORD=your_password
JWT_SECRET=your_secret
```

3. Run the application:

```
mvn spring-boot:run
```

---

### 🔹 Frontend Setup

1. Navigate to frontend folder:

```
cd fronted
```

2. Install dependencies:

```
npm install
```

3. Run the app:

```
npm run dev
```

---

## 🔗 API Endpoints (Sample)

| Method | Endpoint       | Description       |
| ------ | -------------- | ----------------- |
| POST   | /auth/login    | User Login        |
| POST   | /auth/register | User Registration |
| GET    | /expenses      | Get Expenses      |
| POST   | /income        | Add Income        |

---

## 🔐 Security

* JWT-based authentication
* Environment variables for sensitive data
* No hardcoded credentials


---

## 👨‍💻 Author

**Prince Singh**

---

## ⭐ Show your support

If you like this project, give it a ⭐ on GitHub!
