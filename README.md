🩸 Blood Bank Management System
A Django-based web application designed to efficiently manage blood donation and blood request operations. It connects donors, patients, and admin in a structured workflow to ensure smooth and transparent blood stock management.

📌 Overview
The Blood Bank Management System is built to simplify and digitize blood bank operations. It provides role-based access for Admin, Donor, and Patient.

👨‍💼 Admin manages blood stock, donors, patients, and approvals
🧑 Donor can donate blood and request blood
🧑‍⚕️ Patient can request blood without admin approval
The system ensures proper tracking of donations and requests with status updates.

🚀 Features
👨‍💼 Admin
Manage donors and patients
Approve or reject blood donation requests
Approve or reject blood requests
Monitor blood stock by group
View complete transaction history
Update blood inventory
🧑 Donor
Register and login
Donate blood (requires admin approval)
Request blood from system
View donation history
Track request status (Pending / Approved / Rejected)
🧑 Patient
Register and login
Request blood by group and units
View request history
Track status and dashboard statistics
🏗️ Project Structure
bloodbankmanagement-master/
│
├── bloodbankmanagement/ # Django project settings
│ ├── init.py
│ ├── settings.py
│ ├── urls.py
│ ├── asgi.py
│ └── wsgi.py
│
├── app/ # Main application
│ ├── migrations/
│ ├── templates/ # HTML templates
│ ├── static/ # CSS, JS, images
│ ├── init.py
│ ├── admin.py
│ ├── apps.py
│ ├── models.py # Database models
│ ├── views.py # Business logic
│ ├── urls.py # App routes
│ └── forms.py # Forms
│
├── db.sqlite3 # SQLite database
├── manage.py # Django project manager
├── requirements.txt # Project dependencies
└── README.md # Project documentation
🛠️ Tech Stack
Python 🐍
Django 🌐
SQLite 🗄️
HTML, CSS, Bootstrap 🎨
⭐ Support
If you like this project, don’t forget to give it a ⭐ on GitHub!
