# 🏥 Doctor Appointment System

A full-stack Doctor Appointment System developed to simplify the process of booking and managing medical appointments. The application allows patients to register, book appointments, and manage their profiles, while doctors can manage appointments and patient records.

> **Note:** This project is configured to run only in a local development environment using localhost and a locally installed MongoDB database.

---

## Features

### Patient
- User Registration and Login
- Book Doctor Appointments
- View Appointment History
- Manage Profile
- Cancel Appointments

### Doctor
- Secure Login
- View Scheduled Appointments
- Manage Patient Information
- Update Appointment Status

### Admin
- Manage Doctors
- Manage Patients
- View All Appointments
- Dashboard for System Management

---

## Technologies Used

### Frontend
- React.js
- HTML5
- CSS3
- JavaScript
- Bootstrap

### Backend
- Node.js
- Express.js

### Database
- MongoDB (Local Installation)

### Other Tools
- Git
- GitHub
- npm

---

## Project Structure

```
Doctor-Appointment-System/
│
├── client/
│   ├── src/
│   ├── public/
│   └── package.json
│
├── server/
│   ├── config/
│   ├── controllers/
│   ├── models/
│   ├── routes/
│   ├── middleware/
│   ├── package.json
│   └── server.js
│
└── README.md
```

---

## Prerequisites

Before running the project, install the following:

- Node.js
- npm
- MongoDB Community Server
- Git

---

## Installation

### 1. Clone the repository

```bash
git clone https://github.com/YOUR_USERNAME/Doctor-Appointment-System.git
```

### 2. Navigate to the project

```bash
cd Doc-Appointment-System
```

### 3. Install frontend dependencies

```bash
cd client
npm install
```

### 4. Install backend dependencies

```bash
cd ../server
npm install
```

---

## Configure MongoDB

Start your local MongoDB service.

Default MongoDB connection:

```
mongodb://127.0.0.1:27017/doctorappointment
```

If your project uses a different database name, update the connection string accordingly.

---

## Environment Variables

Create a `.env` file inside the **server** folder.

Example:

```env
PORT=5000

MONGO_URI=mongodb://127.0.0.1:27017/doctorappointment

JWT_SECRET=your_secret_key
```

---

## Running the Project

### Start Backend

```bash
cd server
npm start
```

or

```bash
npm run dev
```

### Start Frontend

```bash
cd client
npm start
```

---

## Application URLs

Frontend

```
http://localhost:3000
```

Backend API

```
http://localhost:5000
```

---

## Database

This project uses a **locally installed MongoDB** database.

Cloud databases such as MongoDB Atlas are **not configured**.

---

## Screenshots

Add screenshots of:

- Home Page
- Login Page
- Registration Page
- Doctor Dashboard
- Patient Dashboard
- Appointment Booking

---

## Future Improvements

- Online Payment Integration
- Email Notifications
- Video Consultation
- Prescription Management
- Medical Report Upload
- Responsive Mobile Design

---

## License

This project is developed for educational and learning purposes.

---
