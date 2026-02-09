
# 📝 ExamApp – Online Examination System (Django)

## 📌 Project Overview

**ExamApp** is a Django-based web application designed to conduct online examinations.
It allows users to **register, log in, select subjects, attempt questions, and view scores**.
The project follows Django’s **MVT (Model–View–Template)** architecture and also includes **serializers**, indicating API readiness.

---

## 🚀 Features

* 👤 User Registration & Login
* 📚 Subject-wise Exams
* ❓ Question Navigation & Form Submission
* 🧮 Automatic Score Calculation
* 📊 Result Storage
* 🔐 Admin Panel for Management
* 🌐 Template-based UI (HTML)
* 🔄 API support using serializers

---

## 🏗️ Project Structure

```
examapp/
│
├── examapp/
│   ├── __init__.py
│   ├── admin.py          # Admin configuration
│   ├── apps.py           # App configuration
│   ├── models.py         # Database models
│   ├── serializers.py    # API serializers
│   ├── urls.py           # App-level URLs
│   ├── views.py          # Business logic
│   ├── tests.py          # Test cases
│
├── migrations/
│   ├── 0001_initial.py
│   ├── 0002_result_userdata.py
│
├── templates/
│   ├── login.html
│   ├── registration.html
│   ├── subject.html
│   ├── questionform.html
│   ├── questionnavigation.html
│   ├── score.html
│
├── __pycache__/
├── .git/
└── README.md
```

---

## 🛠️ Technologies Used

* **Backend:** Python, Django
* **Frontend:** HTML, Django Templates
* **Database:** SQLite (default Django DB)
* **API:** Django REST Framework (Serializers)
* **Version Control:** Git

---

## 🧠 Core Modules Explained

### 🔹 Models (`models.py`)

* Stores:

  * User data
  * Questions
  * Exam results
* Uses Django ORM for database interaction

---

### 🔹 Views (`views.py`)

* Handles:

  * Login & Registration logic
  * Question display
  * Answer submission
  * Score calculation

---

### 🔹 Templates (`templates/`)

| File                      | Purpose                      |
| ------------------------- | ---------------------------- |
| `login.html`              | User login page              |
| `registration.html`       | New user registration        |
| `subject.html`            | Subject selection            |
| `questionform.html`       | Question answering           |
| `questionnavigation.html` | Navigation between questions |
| `score.html`              | Display final score          |

---

### 🔹 Serializers (`serializers.py`)

* Converts Django models into JSON
* Enables API-based access for:

  * Mobile apps
  * Frontend frameworks (React, Angular)

---

## ▶️ How to Run the Project

### 1️⃣ Clone the Repository

```bash
git clone https://github.com/your-username/examapp.git
cd examapp
```

### 2️⃣ Create Virtual Environment

```bash
python -m venv venv
venv\Scripts\activate
```

### 3️⃣ Install Dependencies

```bash
pip install django djangorestframework
```

### 4️⃣ Apply Migrations

```bash
python manage.py makemigrations
python manage.py migrate
```

### 5️⃣ Create Superuser

```bash
python manage.py createsuperuser
```

### 6️⃣ Run Server

```bash
python manage.py runserver
```

Open browser:

```
http://127.0.0.1:8000/
```

---

## 🔐 Admin Panel

Access admin panel at:

```
http://127.0.0.1:8000/admin/
```

Use superuser credentials to:

* Add questions
* Manage users
* View results

---

## 📈 Future Enhancements

* ⏱️ Timer-based exams
* 📱 Mobile-friendly UI
* 📊 Detailed analytics
* 🎯 Randomized questions
* ☁️ Deployment on cloud

---

## 👨‍💻 Author

**Akshada Kad**
Final Year Project – Online Examination System

