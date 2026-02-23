# ⚙️ Bus Ticket Booking System (Backend API)

[![Python](https://img.shields.io/badge/Python-3.8+-3776AB?style=for-the-badge&logo=python&logoColor=white)](https://www.python.org/)
[![Django](https://img.shields.io/badge/Django-092E20?style=for-the-badge&logo=django&logoColor=white)](https://www.djangoproject.com/)
[![DRF](https://img.shields.io/badge/Django_REST_Framework-A30000?style=for-the-badge&logo=django&logoColor=white)](https://www.django-rest-framework.org/)

This is the robust backend engine for the Bus Ticket Booking System. It manages the database, user authentication, and ticket booking logic, serving data via a RESTful API to the React frontend.

## 🔗 Related Repositories
* *Frontend UI:* [React-Frontend-BusTicketBooking-System](https://github.com/himateja27/React-Frontend-BusTicketBooking-System)

## ✨ Core Functionalities
* *RESTful API:* Endpoints for bus schedules, seat availability, and ticket bookings.
* *Database Management:* Optimized models for Buses, Routes, Seats, and Users.
* *Authentication:* Secure user login and registration using JWT or Token-based authentication.
* *Booking Logic:* Prevents double-booking through server-side validation.
* *Admin Dashboard:* Full CRUD interface for managing buses, routes, and viewing ticket sales.

## 🛠️ Tech Stack
* *Language:* Python 3.x
* *Framework:* Django & Django REST Framework (DRF)
* *Database:* SQLite (Development) / PostgreSQL (Production)
* *CORS Handling:* django-cors-headers for seamless React integration.

## 📦 Installation & Setup

### Prerequisites
* Python installed on your machine.
* Virtualenv library (pip install virtualenv).

### Step-by-Step Setup
1. *Clone the repository:*
   ```bash
   git clone [https://github.com/himateja27/Django-Backend-BusTicketBooking-System.git](https://github.com/himateja27/Django-Backend-BusTicketBooking-System.git)

2.Create and activate a Virtual Environment :
   # Create venv
   python -m venv venv

   # Activate (Windows)
  .\venv\Scripts\activate

  # Activate (Mac/Linux)
  source venv/bin/activate

3.Install dependencies : 
   pip install -r requirements.txt

4.Apply migrations & start server:
   python manage.py makemigrations
   python manage.py migrate
   python manage.py runserver

👤 Author
V Hima Teja
Python Full Stack Developer
Developed with ❤️ as part of a Python Full Stack Project.

### Pro-Tips for this Repository:
1.  *requirements.txt:* Ensure you have generated this file in your backend folder by running pip freeze > requirements.txt. This allows others to install your dependencies easily.
2.  *CORS Settings:* In your settings.py, make sure your CORS_ALLOWED_ORIGINS includes your Vercel URL so the React app can talk to the Django app.
3.  *Link them up:* Now that you have both READMEs, anyone visiting your backend can easily find the frontend, and vice-versa. 

*Since you're a Full Stack Developer, would you like me to help you create a custom "Profile README" that shows off your Python and React skills on your main profile page?*
