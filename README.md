
# 🏥 MERN Stack Hospital Management System

**Developed by Prabhat Vaidhya**

A full-featured, secure, and responsive **Hospital Management System** built using the MERN stack (MongoDB, Express, React, Node). This application allows hospital staff, doctors, and patients to manage appointments, records, and communication—all in one centralized platform.

---

## 🚀 Key Features

- 🔐 **Role-Based Access**: Patients, Doctors, and Admins
- 📅 **Appointment Booking System**
- 🗃️ **Patient Record Management**
- 📋 **Doctor Scheduling**
- 📈 **Admin Dashboard for System Monitoring**
- 📧 **Email Notifications (optional)**

---

## 🧰 Tech Stack

| Layer      | Technology Used                      |
|------------|---------------------------------------|
| Frontend   | React.js, Tailwind CSS, Axios         |
| Backend    | Node.js, Express.js                   |
| Database   | MongoDB with Mongoose ORM             |
| Auth       | JWT (JSON Web Token), bcrypt          |
| APIs       | RESTful API architecture              |

---

## 🧱 Project Structure

```
hospital-management-system/
├── backend/
│   ├── controllers/
│   ├── middleware/
│   ├── models/
│   ├── routes/
│   └── server.js
├── frontend/
│   ├── public/
│   └── src/
│       ├── components/
│       ├── pages/
│       ├── context/
│       └── App.js
```

---

## ⚙️ Getting Started

### 📦 Prerequisites

- Node.js v16+
- MongoDB
- npm or yarn

### 🔧 Installation Steps

```bash
git clone https://github.com/prabhat-vaidhya/hospital-management-system.git
cd hospital-management-system
```

#### Backend Setup

```bash
cd backend
cp .env.example .env
npm install
npm run dev
```

> Runs backend server on `http://localhost:5000`

#### Frontend Setup

```bash
cd ../frontend
cp .env.example .env
npm install
npm start
```

> Runs React app on `http://localhost:3000`

---

## 🔐 Environment Variables

### Backend `.env`

```env
PORT=5000
MONGO_URI=mongodb://localhost:27017/hospital
JWT_SECRET=your_jwt_secret
```

### Frontend `.env`

```env
REACT_APP_API_URL=http://localhost:5000
```

---

## 📜 Available Scripts

| Location   | Script         | Description                  |
|------------|----------------|------------------------------|
| Backend    | `npm run dev`  | Start backend with Nodemon  |
| Frontend   | `npm start`    | Start React frontend         |
| Frontend   | `npm run build`| Build production frontend    |

---

## 🔬 Research and Design Focus

- Focus on **modular design** for hospital operations.
- Integrated **secure authentication** for sensitive data.
- Designed for **easy deployment** and scalability.
- Optimized for both **doctors and patients** using responsive UIs.

---

## 📄 License

This project is licensed under the **MIT License**.  
See the [LICENSE](./LICENSE) file for more details.

---

## 👨‍💻 Author

**Prabhat Vaidhya**  


---

> *A production-grade hospital management system crafted using modern full-stack development practices.*
