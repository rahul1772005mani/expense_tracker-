# 💰 Expense Tracker (Budget Management) – MERN Stack with Firebase Authentication

## 📌 Project Overview

The Expense Tracker is a full-stack web application built using the MERN stack (MongoDB, Express.js, React.js, Node.js) integrated with Firebase Authentication. The application helps users manage their personal finances by tracking income, expenses, and budgeting effectively.

---

## 🎯 Objectives

* To develop a secure and scalable full-stack application
* To enable users to track daily expenses
* To provide insights into spending habits using analytics
* To implement authentication using Firebase for secure access

---

## 🛠️ Technologies Used

### Frontend:

* React.js
* Axios
* CSS

### Backend:

* Node.js
* Express.js

### Database:

* MongoDB Atlas

### Authentication:

* Firebase Authentication

### Tools:

* VS Code
* Postman (API testing)

---

## 🧱 System Architecture

The application follows a client-server architecture:

* React frontend interacts with backend APIs
* Firebase handles authentication
* Backend verifies user tokens
* MongoDB stores user and expense data

---

## 🔐 Authentication Flow

1. User signs up/login using Firebase
2. Firebase returns a JWT token
3. Token is sent to backend in headers
4. Backend verifies token using Firebase Admin SDK
5. User is authorized to access protected routes

---

## ✨ Features

### 👤 User Authentication

* Signup/Login using Firebase
* Secure token-based authentication
* Persistent login using auth state

### 📊 Dashboard

* Overview of expenses
* Simple and responsive UI

### 💸 Expense Management

* Add expenses
* View expenses
* Delete expenses
* Categorize spending

### 🔒 Security

* Protected API routes
* Token verification
* Secure database access

---

## 📂 Project Structure

```
expense-tracker/
│
├── backend/
│   ├── models/
│   ├── routes/
│   ├── middleware/
│   ├── server.js
│   └── .env
│
├── frontend/
│   ├── src/
│   ├── components/
│   ├── App.js
│   └── firebase.js
```

---

## ⚙️ Installation & Setup

### 1️⃣ Clone Repository

```
git clone <your-repo-link>
cd expense-tracker
```

---

### 2️⃣ Backend Setup

```
cd backend
npm install
```

Create `.env` file:

```
MONGO_URI=your_mongodb_connection_string
```

Run backend:

```
node server.js
```

---

### 3️⃣ Frontend Setup

```
cd frontend
npm install
npm start
```

---

## 🌐 API Endpoints

| Method | Endpoint          | Description      |
| ------ | ----------------- | ---------------- |
| GET    | /api/expenses     | Get all expenses |
| POST   | /api/expenses     | Add new expense  |
| DELETE | /api/expenses/:id | Delete expense   |

---

## 📊 Future Enhancements

* Add charts (Pie/Bar graphs)
* Budget alerts & notifications
* Edit expense functionality
* Monthly reports & analytics
* Mobile app version

---

## 🚀 Conclusion

The Expense Tracker application demonstrates the integration of modern web technologies to build a secure and scalable financial management system. The use of Firebase Authentication enhances security, while the MERN stack ensures flexibility and performance.

This project provides a strong foundation for real-world full-stack development.

---

## 👨‍💻 Author

Your Name
(Replace with your details)

---

## 📜 License

This project is for educational purposes.
