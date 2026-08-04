# 📚 Library Management System (MERN Stack)

A full-stack **Library Management System** built using the **MERN Stack (MongoDB, Express.js, React.js, and Node.js)**. The application provides separate dashboards for **Admin, Librarian, and Student**, enabling efficient library operations such as book management, issue/return requests, user management, and fine tracking.

---

## 🚀 Features

### 👨‍🎓 Student

* User Registration & Login (JWT Authentication)
* Browse and Search Books
* Request Book Issue
* Return Borrowed Books
* View Borrowing History
* Check Due Dates & Fine Details

### 📚 Librarian

* Add, Update & Delete Books
* Approve/Reject Issue Requests
* Process Book Returns
* Upload Book Cover Images
* View Issued Books
* Library Dashboard

### 👨‍💼 Admin

* Manage Users
* Assign Librarian Roles
* Monitor Library Statistics
* Manage System Data

---

## 🛠️ Tech Stack

### Frontend

* React.js
* React Router
* Axios
* Bootstrap / CSS
* React Icons
* Context API

### Backend

* Node.js
* Express.js
* MongoDB Atlas
* Mongoose
* JWT Authentication
* Bcrypt
* Multer
* Cloudinary
* Nodemailer

---

## 📂 Project Structure

```
Library-Management-System/
│
├── frontend/
│   ├── src/
│   ├── public/
│   └── package.json
│
├── backend/
│   ├── controllers/
│   ├── models/
│   ├── routes/
│   ├── middleware/
│   ├── config/
│   └── package.json
│
└── README.md
```

---

## ⚙️ Installation

### Clone Repository

```bash
git clone https://github.com/YOUR_USERNAME/library-management-system.git
```

### Install Dependencies

#### Backend

```bash
cd backend
npm install
```

#### Frontend

```bash
cd frontend
npm install
```

---

## 🔑 Environment Variables

### Backend (.env)

```env
PORT=5000
MONGO_URI=your_mongodb_connection_string
JWT_SECRET=your_jwt_secret
EMAIL_USER=your_email
EMAIL_PASS=your_email_password
CLOUD_NAME=your_cloudinary_name
CLOUD_API_KEY=your_cloudinary_api_key
CLOUD_API_SECRET=your_cloudinary_api_secret
```

### Frontend (.env)

```env
VITE_BACKEND_URL=http://localhost:5000
```

---

## ▶️ Run the Project

### Backend

```bash
npm start
```

or

```bash
nodemon index.js
```

### Frontend

```bash
npm run dev
```

---

## 📸 Screenshots

Add screenshots of:

* Home Page
* Student Dashboard
* Librarian Dashboard
* Admin Dashboard
* Book Management
* Login & Registration

---

## 🎯 Future Enhancements

* QR Code-Based Book Issue
* Email Notifications
* Dark Mode
* Book Reservation System
* Advanced Search & Filters
* Analytics Dashboard
* Mobile Responsive UI

---

## 👩‍💻 Developed By

**Usha Ramineni**

* 🎓 B.E. – Information Science & Engineering
* 💻 MERN Stack Developer


---

## ⭐ Support

If you found this project helpful, consider giving it a **⭐ Star** on GitHub.
