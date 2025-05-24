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
## Installation Guides
pip install django djangorestframework drf-yasg django-environ mysqlclient

- Install RabbitMQ on Linux Mint
- To install RabbitMQ on Linux Mint, you can follow these steps:

- Update your system:
- sudo apt-get update
- sudo apt-get upgrade

- Install Erlang, which is a dependency for RabbitMQ: You can get the latest version of Erlang from Team RabbitMQ on Launchpad. Add the repository and install Erlang:

- wget https://github.com/rabbitmq/signing-keys/releases/download/2.0/rabbitmq-adv.key
- sudo apt-key add rabbitmq-adv.key
- echo 'deb https://dl.cloudsmith.io/public/rabbitmq/rabbitmq-erlang/deb/ubuntu/ $(lsb_release -cs) main' | sudo tee /etc/apt/sources.list.d/rabbitmq.list
- echo 'deb https://dl.cloudsmith.io/public/rabbitmq/rabbitmq-server/deb/ubuntu/ $(lsb_release -cs) main' | sudo tee /etc/apt/sources.list.d/rabbitmq.list
- sudo apt-get update
- sudo apt-get install erlang

- Install RabbitMQ:
- sudo apt-get install rabbitmq-server
- Start the RabbitMQ service:
- sudo systemctl start rabbitmq-server

- Enable RabbitMQ to start automatically on boot:
- sudo systemctl enable rabbitmq-server
- Optionally, enable the RabbitMQ Management Console:
- sudo rabbitmq-plugins enable rabbitmq_management

- Access the RabbitMQ Management Console via a web browser at http://localhost:15672/. The default username and password are both "guest".

## 🔗 Useful Links

* [Django Documentation](https://docs.djangoproject.com/en/stable/)
* [DRF Documentation](https://www.django-rest-framework.org/)
* [drf-yasg Swagger Docs](https://github.com/axnsan12/drf-yasg)
* [Celery Docs](https://docs.celeryq.dev/en/stable/)
* [RabbitMQ Docs](https://www.rabbitmq.com/)

---


