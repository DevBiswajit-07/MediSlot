# 🏥 MediSlot - Doctor Appointment Booking System

MediSlot is a full-stack **MERN (MongoDB, Express.js, React.js, Node.js)** web application that simplifies the process of booking doctor appointments online. It provides separate dashboards for **Patients, Doctors, and Administrators**, allowing efficient appointment management, doctor profile management, and secure authentication.

---

## 🚀 Features

### 👤 Patient Module

* Secure user registration and login using JWT authentication.
* Browse available doctors by specialty.
* View detailed doctor profiles.
* Book appointments with preferred date and time.
* Cancel booked appointments.
* View appointment history.
* Update personal profile information.

### 👨‍⚕️ Doctor Module

* Secure doctor login.
* View daily appointment schedule.
* Manage appointment status.
* Update doctor profile.
* Dashboard displaying appointment statistics and earnings.

### 👨‍💼 Admin Module

* Secure admin authentication.
* Add new doctors with profile image upload.
* Manage doctor availability.
* View all registered doctors.
* View and manage all appointments.
* Monitor overall system statistics through the dashboard.

---

## 🛠️ Tech Stack

### Frontend

* React.js
* Vite
* React Router DOM
* Axios
* Tailwind CSS
* React Toastify

### Backend

* Node.js
* Express.js
* MongoDB
* Mongoose
* JWT Authentication
* bcrypt
* Multer
* Cloudinary

---

## 📂 Project Structure

```
MediSlot/
│
├── frontend/              # Patient Web Application
│   ├── src/
│   ├── public/
│   └── package.json
│
├── admin/                 # Admin & Doctor Dashboard
│   ├── src/
│   ├── public/
│   └── package.json
│
├── backend/
│   ├── config/
│   ├── controllers/
│   ├── middleware/
│   ├── models/
│   ├── routes/
│   ├── server.js
│   └── package.json
│
└── README.md
```

---

## 🔐 Authentication

The application uses **JSON Web Token (JWT)** based authentication.

* User Login
* Doctor Login
* Admin Login
* Protected API Routes
* Password Encryption using bcrypt

---

## ☁️ Image Storage

Doctor profile images are uploaded securely using **Cloudinary**, enabling efficient cloud-based image storage and delivery.

---

## 🗄️ Database

MongoDB is used as the primary database.

Collections include:

* Users
* Doctors
* Appointments

---

## ⚙️ Installation

### 1. Clone the Repository

```bash
git clone https://github.com/devBiswajit-07/MediSlot.git
```

---

### 2. Navigate to the Project

```bash
cd MediSlot
```

---

### 3. Install Dependencies

#### Backend

```bash
cd backend
npm install
```

#### Frontend

```bash
cd ../frontend
npm install
```

#### Admin

```bash
cd ../admin
npm install
```

---

### 4. Configure Environment Variables

Create a `.env` file inside the **backend** directory.

Example:

```env
PORT=4000

MONGODB_URI=your_mongodb_connection_string

JWT_SECRET=your_jwt_secret

CLOUDINARY_NAME=your_cloudinary_cloud_name
CLOUDINARY_API_KEY=your_cloudinary_api_key
CLOUDINARY_SECRET_KEY=your_cloudinary_secret_key

ADMIN_EMAIL=admin@example.com
ADMIN_PASSWORD=your_admin_password
```

---

### 5. Run the Backend

```bash
cd backend
npm run server
```

or

```bash
nodemon server.js
```

---

### 6. Run the Frontend

```bash
cd frontend
npm run dev
```

---

### 7. Run the Admin Dashboard

```bash
cd admin
npm run dev
```

---

## 📸 Application Modules

* Patient Portal
* Doctor Dashboard
* Admin Dashboard
* Appointment Booking
* Appointment Management
* Doctor Management
* User Authentication
* Cloud Image Upload

---

## 🔄 Application Workflow

1. User registers and logs into the system.
2. User browses available doctors.
3. User books an appointment by selecting date and time.
4. Appointment details are stored in MongoDB.
5. Doctor can view and manage appointments.
6. Admin manages doctors, appointments, and system data.

---

## 🎯 Learning Outcomes

This project helped strengthen practical knowledge of:

* Full Stack MERN Development
* REST API Development
* MongoDB Database Design
* JWT Authentication
* MVC Architecture
* CRUD Operations
* Cloudinary Image Upload
* React State Management
* API Integration using Axios

---

## 🔮 Future Enhancements

* Online Payment Gateway Integration
* Email Notifications
* SMS Appointment Reminders
* Video Consultation
* Prescription Management
* Medical Report Upload
* Search & Filter Doctors
* Appointment Rescheduling
* Responsive Mobile Application

---

## 👨‍💻 Author

**Biswajit**

MCA Student | MERN Stack Developer

---

## ⭐ If you found this project useful, consider giving it a Star on GitHub!

