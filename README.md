# Child Vaccination Monitoring and Notification System

A Django-based web application for monitoring child vaccinations and sending automated notifications using Celery.  
This system helps hospitals and healthcare providers track vaccination schedules, notify parents, and maintain records effectively.

---

## Features

- **User Registration & Management:** Register children and maintain vaccination records.
- **Vaccination Tracking:** Track due, upcoming, and completed vaccinations.
- **Automated Notifications:** Send reminders via background tasks using Celery.
- **Admin Panel:** Manage users, vaccination schedules, and system settings.
- **Scalable Architecture:** Django backend with asynchronous task handling via Celery.

---

## Tech Stack

- **Backend:** Python 3, Django
- **Task Queue:** Celery (with Redis or RabbitMQ as broker)
- **Database:** SQLite (default) — can be switched to PostgreSQL/MySQL
- **Frontend:** HTML, CSS, Bootstrap (Django templates)
- **Environment:** Virtualenv / venv (recommended)

---

