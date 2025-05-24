---

# 🧳 alxtravelapp

**alxtravelapp** is a real-world Django application designed to serve as the foundation for a scalable travel listing platform. This project focuses on establishing robust backend infrastructure, integrating Swagger for API documentation, and using MySQL for reliable data management — all while following industry best practices.

---

## 📚 About the Project

This milestone introduces learners to advanced Django project setup and backend architecture. You will:

* Structure a Django project using modular, production-ready configurations.
* Implement MySQL as a primary database.
* Generate interactive API documentation using Swagger (via `drf-yasg`).
* Prepare the application for future scalability, background processing, and seamless collaboration.

---

## 🎯 Learning Objectives

As a professional developer, you will:

* ✅ Bootstrap Django projects with scalable architecture.
* ✅ Use environment variables securely with `django-environ`.
* ✅ Set up and configure MySQL in Django.
* ✅ Integrate Swagger for auto-generated API documentation.
* ✅ Prepare the app for background tasks with Celery and RabbitMQ.
* ✅ Enable CORS support for API flexibility.
* ✅ Structure your codebase for Git-based team collaboration.

---

## ✅ Requirements

Before starting, ensure you are familiar with:

* Django & Django REST Framework (DRF)
* MySQL database management
* Version control using Git
* Basic environment variable management with `.env` files

---

## 🚀 Key Highlights

### 1. **Project Initialization**

* Django project: `alxtravelapp`
* App: `listings`

### 2. **Dependency Management**

Essential packages:

```bash
pip install django djangorestframework django-cors-headers drf-yasg celery django-environ
```

Other tools:

* RabbitMQ (for future task queuing)

### 3. **Settings Configuration**

* Use `.env` with `django-environ` to manage sensitive credentials.
* Configure `settings.py` to use MySQL.
* Enable CORS and REST framework.

### 4. **Swagger Integration**

* Use `drf-yasg` to document all API endpoints.
* Swagger UI available at: [`/swagger/`](http://localhost:8000/swagger/)

### 5. **Version Control**

* Initialize Git:

  ```bash
  git init
  git add .
  git commit -m "Initial project setup with Swagger and MySQL"
  ```
* Push to GitHub repo: `alxtravelapp`

---

## 🛠️ Tasks

### ✅ Task 0: Django Project Setup with API Docs & DB Configuration

* Set up Django project `alx_travel_app`
* Create `listings` app
* Configure:

  * MySQL (via environment variables)
  * REST framework
  * CORS headers
  * Swagger (`drf-yasg`)
* Initialize Git and push to GitHub

---

## 📁 Project Structure

```
alxtravelapp/
│
├── alx_travel_app/
│   ├── __init__.py
│   ├── settings.py
│   ├── urls.py
│   └── wsgi.py
│
├── listings/
│   ├── models.py
│   ├── views.py
│   ├── urls.py
│   └── serializers.py
│
├── .env
├── manage.py
└── README.md
```

---

## 🔗 Useful Links

* [Django Documentation](https://docs.djangoproject.com/en/stable/)
* [DRF Documentation](https://www.django-rest-framework.org/)
* [drf-yasg Swagger Docs](https://github.com/axnsan12/drf-yasg)
* [Celery Docs](https://docs.celeryq.dev/en/stable/)
* [RabbitMQ Docs](https://www.rabbitmq.com/)

---

Let me know if you want this exported into a file or need a badge/logo section!
