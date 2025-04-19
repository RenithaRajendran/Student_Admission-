# Student Admission Web Application

## 📌 Project Overview

This is a Flask-based web application that allows students to submit admission applications and enables admins to review, approve, or reject them. Upon approval, the system generates a downloadable admission letter in PDF format.

---

## 🚀 Features

- Student application form with personal info, academic background, and file upload (ID proof, degree certificate).
- Admin panel to review, approve, or reject applications.
- Generates admission letter as PDF upon approval.
- Uploads and stores documents securely.
- Basic form validation (email, required fields).
- MySQL/PostgreSQL database integration.

---

## 🛠️ Technology Stack

- **Backend**: Python, Flask
- **Database**: MySQL / PostgreSQL (switchable), SQLAlchemy ORM
- **Frontend**: HTML, CSS
- **File Upload & Validation**: Flask-WTF, WTForms
- **PDF Generation**: ReportLab / xhtml2pdf / WeasyPrint
- **Authentication**: Flask-Login (for admin)
- **Migration**: Flask-Migrate
- **Testing**: `pytest`, `unittest`
- **Environment**: Python 3.12, virtualenv

---

## 📥 Installation Instructions

### 🔧 Prerequisites

- Python 3.10+
- pip
- MySQL or PostgreSQL installed
- Git

### 🔌 Setup

```bash
git clone https://github.com/your-username/student-admission-app.git
cd student-admission-app
python -m venv venv
venv\Scripts\activate  # for Windows
# source venv/bin/activate  # for Mac/Linux
pip install -r requirements.txt

