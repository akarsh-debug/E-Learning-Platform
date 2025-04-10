# 🧠 E-Learning Platform (MERN Stack)

[![MERN Stack](https://img.shields.io/badge/Stack-MERN-%2300f.svg?style=flat&logo=MERN)](https://www.mongodb.com/mern-stack)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)

An online learning platform built using the MERN stack (MongoDB, Express, React, Node.js) that enables flexible learning, course management, and administrative oversight. Supports interactive features, certifications, and secure payments.

---

## 🚀 Features

### 👩🏫 Instructors
- **Course Builder** with drag-and-drop modules
- **Student Analytics** dashboard
- **Content Management** (videos, PDFs, quizzes)
- **Revenue Tracking** for paid courses

### 👨🎓 Students
- **Progress Tracking** with completion percentage
- **Certification System** with PDF generation
- **Discussion Forums** per course
- **Bookmarking** system for lessons

### 🛠️ Admins
- User role management
- Content moderation tools
- Payment transaction logs
- System health monitoring

---

## 🛠️ Tech Stack

| **Frontend**       | **Backend**         | **Utilities**             |
|---------------------|---------------------|---------------------------|
| React 18            | Node.js 20          | MongoDB Atlas             |
| Redux Toolkit       | Express 4           | Mongoose ODM              |
| Material UI v5      | JWT Authentication  | Cloudinary Storage        |
| React Router 6      | Stripe API          | Nodemailer                |
| Axios               | Socket.IO           | Jest (Testing)            |

---

## 🖥️ Installation

### Prerequisites
- Node.js 18+
- MongoDB Atlas account
- Stripe API keys

1. **Clone Repository**
```bash
git clone https://github.com/yourusername/e-learning-mern.git
cd e-learning-mern
```

2. **Backend Setup**
```bash
cd server
npm install
echo "PORT=5000
MONGO_URI=mongodb+srv://<user>:<password>@cluster.mongodb.net/elearning
JWT_SECRET=your_jwt_secret_here
STRIPE_KEY=your_stripe_secret_key" > .env
npm start
```

3. **Frontend Setup**
```bash
cd ../client
npm install
echo "REACT_APP_API=http://localhost:5000
REACT_APP_STRIPE_KEY=your_stripe_publishable_key" > .env
npm start
```

---

## 📸 Screenshots

### Home Page
![Home Page](https://github.com/user-attachments/assets/c99cffce-a3ac-4c2d-a272-b50ca7ea224e)

### Course Catalog
![Course Catalog](https://github.com/user-attachments/assets/bfaf0828-3d19-4bd3-93fe-65118b4cd05b)

### Course Details
![Course Details](https://github.com/user-attachments/assets/453ec2e3-8f53-449c-bec9-f9a734ecfd1f)

### Instructor Dashboard
![Instructor Dashboard](https://github.com/user-attachments/assets/9b576764-6816-4c1c-af1b-a57adf67dc66)

---

## 🎥 Demo Video
[Watch Platform Demo](https://drive.google.com/file/d/1ihu2ZLT9wRR-_s2vNNQMW6P22mkupk5k/view?usp=drivesdk)

---

## 📄 License

Distributed under the MIT License. See `LICENSE` file for more information.

---

> **Note:** Replace all placeholder URLs and credentials with your actual project resources before deployment.
