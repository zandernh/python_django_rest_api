# 📝 Django Blogpost REST API

A lightweight and fully functional REST API built with Django and the Django REST Framework (DRF).
This API allows you to create, read, update, delete, and filter blog posts using clean REST endpoints.

--- 

## 🚀 Features

- 📄 Create new blog posts
- 📚 Retrieve all posts
- 🔍 Filter blog posts by title (case-insensitive)
- ✏️ Update existing posts
- ❌ Delete individual posts
- 🧹 Delete all blog posts at once
- ⚡ Built using Django & Django REST Framework

---

## 🛠️ Tech Stack

- Python
- Django 5.2
- Django REST Framework (DRF)
- SQLite3 (default development database)

---

## 🔗 API Endpoints

### 📚 Get All Blog Posts / Create New Post

GET  /blogposts/

POST /blogposts/

### 🧹 Delete ALL Blog Posts

DELETE /blogposts/

### ✏️ Retrieve / Update / Delete a Single Post

GET     /blogposts/<id>/

PUT     /blogposts/<id>/

PATCH   /blogposts/<id>/

DELETE  /blogposts/<id>/

### 🔍 Filter Blog Posts by Title

GET /blogposts/filter/?title=keyword

---

## 💻 Running the Project Locally

### 1. Clone the repository

git clone git@github.com:zandernh/python_django_rest_api_blogpost.git

cd python_django_rest_api_blogpost

### 2. Create and activate a virtual environment

python -m venv venv

venv\Scripts\activate   (Windows)

source venv/bin/activate (Mac/Linux)

### 3. Install dependencies

pip install -r requirements.txt

### 4. Apply migrations

python manage.py migrate

### 5. Start the development server

python manage.py runserver

---

## 📜 License

This project is open-source and free to use.

--- 

## 🙋‍♂️ Author

Built by Zander Harding
