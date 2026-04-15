# 🌍 Tour Planner Web Application

## 📌 Project Overview
The Tour Planner is a web-based application designed to simplify tour management and booking processes. It allows users to explore available tour packages, view details, and make bookings, while providing administrators with tools to manage tours efficiently.

This project was developed as part of an academic coursework (CSE370) using Flask and a structured backend system.

---

## 🚀 Features

### 👤 User Features
- Browse available tour packages
- View detailed tour information
- Book tours بسهولة (easily)
- User-friendly interface

### 🛠️ Admin Features
- Add, update, and delete tour packages
- Manage bookings
- Maintain structured tour data

---

## 🏗️ Tech Stack

- **Backend:** Python (Flask)
- **Frontend:** HTML, CSS, Bootstrap
- **Database:** SQLite
- **Template Engine:** Jinja2

---

## 📂 Project Structure
tour-planner/
│
├── app.py                # Main Flask app
├── config.py             # Configuration settings (optional)
├── models.py             # Database models
├── requirements.txt      # Dependencies
├── database.db           # SQLite database
│
├── routes/               # Route handlers
│   ├── __init__.py
│   ├── user_routes.py
│   ├── admin_routes.py
│
├── templates/            # HTML templates (Jinja2)
│   ├── base.html
│   ├── index.html
│   ├── tours.html
│   ├── booking.html
│   ├── admin_dashboard.html
│
├── static/               # Static files
│   ├── css/
│   │   └── style.css
│   ├── js/
│   │   └── script.js
│   ├── images/
│
├── instance/             # Instance-specific files (optional)
│   └── config.py
│
└── README.md             # Project documentation
