# 🏥 VitalSync – AI-Powered Smart Hospital Queue & Healthcare Management Platform

*A modern full-stack healthcare platform built with **React**, **Node.js**, **Express**, **MongoDB**, **Socket.IO**, and **Google Gemini AI** to streamline hospital operations through intelligent patient triage, real-time queue management, secure authentication, and digital healthcare workflows.*

> **Built as a collaborative team project. My primary contribution focused on React frontend development, authentication flow, API integration, real-time UI updates, and dashboard implementation.

---

## 🌐 Live Demo

🔗 **Live Demo:** https://vitalsync-new.onrender.com/index.html

A demonstration of the VitalSync healthcare platform showcasing patient management, doctor workflow, AI-assisted healthcare features, and real-time hospital queue management.

---
## 🚀 Key Highlights

* 🤖 AI-powered Emergency Triage using Google Gemini
* ⚡ Real-Time Queue Management with Socket.IO
* 🔐 JWT Authentication & Protected Routes
* 👨‍⚕️ Doctor Dashboard
* 👤 Patient Tracking System
* 📺 TV & Hallway Display
* 🎤 Voice Prescription
* 📄 PDF Prescription Generation
* 📧 Email Prescription Delivery
* 📱 Fully Responsive React UI
* 🔄 REST API Integration with Axios

---

## 🛠 Tech Stack

| Category        | Technology          |
| --------------- | ------------------- |
| Frontend        | React.js, Vite      |
| Styling         | Tailwind CSS        |
| Routing         | React Router DOM    |
| HTTP Client     | Axios               |
| Icons           | Lucide React        |
| Animation       | Framer Motion       |
| Backend         | Node.js, Express.js |
| Database        | MongoDB             |
| Authentication  | JWT, bcrypt         |
| Real-Time       | Socket.IO           |
| AI              | Google Gemini API   |
| PDF             | jsPDF               |
| Email           | Nodemailer          |
| Version Control | Git & GitHub        |

---

## 📁 Project Structure

```text
VitalSync/
│
├── client/
│   ├── public/
│   ├── src/
│   │   ├── assets/
│   │   ├── components/
│   │   ├── context/
│   │   ├── pages/
│   │   ├── Dashboard.jsx
│   │   ├── App.jsx
│   │   ├── main.jsx
│   │   └── config.js
│   ├── package.json
│   └── vite.config.js
│
├── server/
│   ├── models/
│   ├── routes/
│   ├── assets/
│   ├── emailService.js
│   ├── index.js
│   ├── package.json
│   ├── Dockerfile
│   └── docker-compose.yaml
│
└── README.md
```

---

## ✨ Core Features

### Authentication

* Secure Login & Registration
* JWT Authentication
* Protected Routes
* Password Encryption with bcrypt

### Doctor Module

* View Active Queue
* Call Next Patient
* Generate Digital Prescription
* Voice-Assisted Prescription
* AI Clinical Assistance

### Patient Module

* Register/Login
* Queue Tracking
* Appointment Booking
* Live Status Updates
* Prescription Download

### AI Features

* Emergency Detection
* Smart Triage
* AI Follow-up Questions
* AI Prescription Formatting

### Real-Time Features

* Socket.IO Queue Synchronization
* Doctor Dashboard Updates
* TV Display
* Hallway Display
* Live Notifications

---

## 🏗 Authentication Flow

```text
React Login
      │
Axios Request
      │
Express Route
      │
JWT Authentication
      │
Token Stored
      │
Protected Route
      │
Dashboard
```

---

## 🚀 Getting Started

### Clone Repository

```bash
git clone https://github.com/YOUR_USERNAME/VitalSync.git
cd VitalSync
```

### Install Frontend

```bash
cd client
npm install
npm run dev
```

### Install Backend

```bash
cd server
npm install
npm start
```

---

## 👨‍💻 My Contributions

My primary responsibilities in this team project included:

* Developed the React frontend using reusable components.
* Designed responsive user interfaces with Tailwind CSS.
* Implemented React Router navigation.
* Integrated REST APIs using Axios.
* Built JWT-based authentication flow.
* Implemented Protected Routes.
* Integrated Socket.IO for real-time updates.
* Developed Doctor Dashboard.
* Built Patient Tracking interface.
* Developed TV Display and Hallway Display.
* Integrated Voice Prescription.
* Implemented PDF generation using jsPDF.
* Collaborated on backend integration and API testing.

---

## 📌 Future Enhancements

* Video Consultation
* Electronic Health Records (EHR)
* Pharmacy Integration
* Multi-Hospital Support
* Push Notifications
* AI Risk Prediction
* Analytics Dashboard
* CI/CD Deployment
* Docker Production Deployment

---

## ⭐ Acknowledgement

This project was developed as a collaborative team project. The frontend architecture, authentication flow, reusable React components, and real-time user interface were key areas of my contribution.

---

### ⭐ If you found this project interesting, consider giving it a Star!
