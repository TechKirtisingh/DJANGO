# 🎓 Gyan Uday School Management System

A comprehensive School Management System built with Django to streamline student management, attendance tracking, course administration, fee management, and result processing.

![Python](https://img.shields.io/badge/Python-3.10+-blue)
![Django](https://img.shields.io/badge/Django-5.x-green)
![License](https://img.shields.io/badge/License-MIT-yellow)
![Status](https://img.shields.io/badge/Status-Active-success)

---

## 📌 Overview

This project is designed to help educational institutions manage their day-to-day operations efficiently through a centralized web application.

The system provides functionalities for:

* 👨‍🎓 Student Management
* 📚 Course Management
* 📅 Attendance Tracking
* 💰 Fee Management
* 📝 Result Management
* 👤 User Authentication
* 📊 Dashboard Analytics

---

## ✨ Features

### Student Module

* Add new students
* Update student information
* View student records
* Manage student profiles

### Attendance Module

* Mark attendance
* Track attendance records
* Generate attendance reports

### Course Module

* Create courses
* Manage course details
* Assign courses to students

### Fee Module

* Record fee payments
* Track pending fees
* Manage fee history

### Result Module

* Upload examination results
* View academic performance
* Generate result reports

### Authentication

* Secure login system
* User role management
* Session handling

---

## 🛠️ Tech Stack

| Technology        | Purpose             |
| ----------------- | ------------------- |
| Python            | Backend Programming |
| Django            | Web Framework       |
| HTML              | Frontend Structure  |
| CSS               | Styling             |
| SQLite/PostgreSQL | Database            |
| Render            | Deployment          |

---

## 📂 Project Structure

```bash
DJANGO/
│
├── accounts/
├── attendance/
├── courses/
├── dashboard/
├── fees/
├── results/
├── students/
├── templates/
├── static/
├── gyan_uday/
│
├── manage.py
├── requirements.txt
├── Procfile
├── render.yaml
└── .env.example
```

## ⚙️ Installation

### Clone Repository

```bash
git clone https://github.com/TechKirtisingh/DJANGO.git
cd DJANGO
```

### Create Virtual Environment

```bash
python -m venv venv
```

### Activate Virtual Environment

Windows:

```bash
venv\Scripts\activate
```

Linux/Mac:

```bash
source venv/bin/activate
```

### Install Dependencies

```bash
pip install -r requirements.txt
```

### Apply Migrations

```bash
python manage.py migrate
```

### Create Superuser

```bash
python manage.py createsuperuser
```

### Run Development Server

```bash
python manage.py runserver
```

Open:

```bash
http://127.0.0.1:8000/
```

---

## 🚀 Deployment

This project includes:

* Procfile
* render.yaml
* Environment configuration support

Suitable for deployment on:

* Render
* Railway
* Heroku
* VPS Servers

---

## 📸 Screenshots

Add screenshots here:

```md
![Dashboard](screenshots/dashboard.png)

![Students](screenshots/students.png)

![Attendance](screenshots/attendance.png)
```

---

## 🎯 Future Enhancements

* Email Notifications
* Parent Portal
* Online Fee Payment
* SMS Integration
* Advanced Analytics
* REST API Support

---

## 🤝 Contributing

Contributions are welcome.

1. Fork the repository
2. Create a new branch
3. Commit your changes
4. Push the branch
5. Open a Pull Request

---

## 👨‍💻 Author

### Kirti Singh

* GitHub: https://github.com/TechKirtisingh

---

⭐ If you found this project useful, please consider giving it a star.
