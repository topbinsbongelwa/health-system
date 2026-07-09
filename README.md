# health-system
A modern web-based Health Management System designed to streamline healthcare operations by providing secure, role-based access for patients, healthcare staff, and administrators. The system simplifies appointment scheduling, patient record management, medical history tracking, prescriptions, billing, and administrative tasks 


# 🏥 Health Management System (HMS)

A modern, secure, and scalable **Health Management System (HMS)** developed to improve healthcare service delivery by providing role-based access for **Patients**, **Healthcare Staff**, and **Administrators**. The system enables efficient management of patient information, appointments, medical records, prescriptions, billing, and notifications through an intuitive web interface.

---

# 📖 Table of Contents

* Introduction
* Features
* System Roles
* Technologies Used
* Project Architecture
* Folder Structure
* Installation
* Environment Variables
* Database Setup
* Running the Project
* Screenshots
* Future Improvements
* Security
* Contributing
* License
* Authors
* Acknowledgements

---

# 📌 Introduction

Healthcare facilities often struggle with paper-based records and disconnected systems. This project provides a centralized digital platform that simplifies hospital operations while ensuring secure access to patient information.

The application supports three different user roles:

* Patient
* Staff
* Administrator

Each role has its own dashboard with permissions tailored to its responsibilities.

---

# ✨ Features

## Authentication

* User Registration
* Secure Login
* Password Encryption
* Role-Based Access Control
* Session Management
* Logout

---

## Patient Dashboard

* View Personal Profile
* Update Personal Information
* Book Appointments
* View Appointment History
* View Medical Records
* Access Prescriptions
* View Laboratory Results
* Billing Information
* Notifications
* Settings

---

## Staff Dashboard

* Dashboard Overview
* Search Patients
* Manage Appointments
* Create Medical Records
* Update Diagnoses
* Prescribe Medication
* Upload Laboratory Results
* Admit Patients
* Discharge Patients
* Notifications

---

## Admin Dashboard

* Dashboard Analytics
* Manage Patients
* Manage Staff
* Manage Departments
* Manage Users
* Billing Management
* Inventory Management
* Reports
* System Settings
* Audit Logs

---

# 🔐 User Roles

## Patient

Patients can:

* Register an account
* Log in securely
* Book appointments
* View medical records
* View prescriptions
* Receive notifications
* Update profile information

---

## Staff

Healthcare staff can:

* View assigned patients
* Manage appointments
* Record diagnoses
* Create prescriptions
* Upload laboratory results
* Update patient records

---

## Administrator

Administrators can:

* Manage all users
* Add or remove staff
* Assign user roles
* Generate reports
* Manage departments
* Monitor hospital activity
* Configure system settings

---

# 💻 Technologies Used

## Frontend

* HTML5
* CSS3
* JavaScript (ES6)

## Backend

* Node.js
* Express.js

## Database

* MySQL

## Authentication

* JSON Web Token (JWT)
* bcrypt

## File Uploads

* Multer

## Notifications

* Node Schedule
* Email/SMS Integration (Future)

## Version Control

* Git
* GitHub

---

# 🏗️ Project Architecture

```text
Client (HTML/CSS/JavaScript)
            │
            ▼
     Express.js Server
            │
            ▼
 REST API Controllers
            │
            ▼
       MySQL Database
```

---

# 📁 Folder Structure

```text
health-management-system/
│
├── client/
│   ├── assets/
│   │   ├── images/
│   │   ├── icons/
│   │   └── fonts/
│   │
│   ├── css/
│   ├── js/
│   ├── pages/
│   │   ├── login.html
│   │   ├── register.html
│   │   ├── patient/
│   │   ├── staff/
│   │   └── admin/
│   │
│   └── index.html
│
├── server/
│   ├── config/
│   ├── controllers/
│   ├── middleware/
│   ├── models/
│   ├── routes/
│   ├── uploads/
│   ├── services/
│   ├── utils/
│   ├── app.js
│   └── server.js
│
├── database/
│   ├── schema.sql
│   └── seed.sql
│
├── .gitignore
├── package.json
├── README.md
└── LICENSE
```

---

# ⚙️ Installation

Clone the repository:

```bash
git clone https://github.com/YOUR_USERNAME/health-management-system.git
```

Navigate into the project:

```bash
cd health-management-system
```

Install dependencies:

```bash
npm install
```

---

# 🔑 Environment Variables

Create a `.env` file in the project root.

Example:

```env
PORT=5000

DB_HOST=localhost
DB_USER=root
DB_PASSWORD=your_password
DB_NAME=health_management_system

JWT_SECRET=your_secret_key
```

---

# 🗄️ Database Setup

Create a MySQL database:

```sql
CREATE DATABASE health_management_system;
```

Import the schema:

```bash
mysql -u root -p health_management_system < database/schema.sql
```

---

# ▶️ Running the Project

Development mode:

```bash
npm run dev
```

Production mode:

```bash
npm start
```

Open your browser:

```
http://localhost:5000
```

---

# 📊 Database Tables

* Users
* Patients
* Staff
* Administrators
* Appointments
* Medical Records
* Prescriptions
* Laboratory Results
* Billing
* Departments
* Notifications

---

# 📸 Screenshots

Add screenshots here once the project interface has been completed.

Examples:

* Landing Page
* Login
* Registration
* Patient Dashboard
* Staff Dashboard
* Admin Dashboard
* Appointment Management
* Medical Records

---

# 🚀 Future Improvements

* Telemedicine
* Online Payments
* Email Notifications
* SMS Appointment Reminders
* AI Health Assistant
* Pharmacy Integration
* Laboratory Integration
* Electronic Health Records (EHR)
* QR Code Patient Identification
* Mobile Application
* Dark Mode
* Multi-language Support

---

# 🔒 Security Features

* Password Hashing using bcrypt
* JWT Authentication
* Role-Based Access Control
* Input Validation
* Secure API Routes
* SQL Injection Prevention
* Cross-Origin Resource Sharing (CORS)
* Environment Variables for Secrets

---

# 🤝 Contributing

Contributions are welcome.

1. Fork the repository.
2. Create a feature branch.
3. Commit your changes.
4. Push your branch.
5. Open a Pull Request.

---

# 📜 License

This project is licensed under the MIT License.

---

# 👨‍💻 Authors

Developed by the Health Management System Development Team.

---

# 🙏 Acknowledgements

Special thanks to everyone who contributed ideas, testing, and feedback throughout the development of this project.

@Bongelwa,@Donnel,@Donnavan,@Russel

## ⭐ Support

If you found this project useful, please consider giving it a ⭐ on GitHub. It helps others discover the project and motivates continued development.
