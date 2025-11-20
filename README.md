# 🧩 Python Django REST API — User Management

A simple and clean Django REST API designed for storing, retrieving, updating, and deleting user information.
This project demonstrates foundational backend skills using Django and Django REST Framework.

---

## 🎯 Features

- 👤 Create new users
- 📋 Retrieve all users
- 🔍 Retrieve a single user by ID
- ✏️ Update user information
- ❌ Delete individual users
- 💾 Data stored using SQLite (default Django database)
- ⚡ Built entirely with Django & Django REST Framework

---

## 🛠️ Tech Stack

- Python
- Django 5.2
- Django REST Framework
- SQLite3

---

## 🔗 API Endpoints

### 📋 Get All Users

GET /users/

### ➕ Create a New User

POST /users/create/

### 🔎 Retrieve / ✏️ Update / ❌ Delete a User

GET    /users/<id>

PUT    /users/<id>

DELETE /users/<id>

---

## 💻 Running the Project Locally

### 1. Clone the repository

git clone git@github.com:zandernh/python_django_rest_api.git

cd python_django_rest_api

### 2. Create and activate a virtual environment

python -m venv venv

venv\Scripts\activate     (Windows)

source venv/bin/activate  (Mac/Linux)

### 3. Install dependencies

pip install -r requirements.txt

### 4. Apply migrations

python manage.py migrate

### 5. Run the development server

python manage.py runserver

---

## 🧠 How It Works

- The User model stores simple user attributes: name and age
- The serializer handles validation and conversion to JSON
- The API uses function-based views (api_view) to manage CRUD logic
- Endpoints follow clean RESTful design
- Errors return standard HTTP responses (400, 404, etc.)

---

## 📄 License

This project is open-source and free to use.

---

## 🙋‍♂️ Author

Built by Zander Harding
