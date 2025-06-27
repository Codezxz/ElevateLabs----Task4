# 🧑‍💻 Flask REST API: User Management

A simple REST API using Flask to manage user data in-memory. Built for a Python Developer Internship task.

## 🚀 Features

- Create, Read, Update, and Delete (CRUD) user data
- JSON-based RESTful API
- In-memory storage (dictionary)

## 📦 Tech Stack

- Python 3.x
- Flask 2.x
- Render (for deployment)

## 🛠 Installation

```bash
git clone https://github.com/codezxz/flask-user-api.git
cd flask-user-api
pip install -r requirements.txt
python app.py
```

## 🌐 API Endpoints

| Method | Endpoint       | Description         |
|--------|----------------|---------------------|
| GET    | /users         | Get all users       |
| GET    | /users/<id>    | Get user by ID      |
| POST   | /users         | Create a new user   |
| PUT    | /users/<id>    | Update a user       |
| DELETE | /users/<id>    | Delete a user       |

## ☁️ Deployment on Render

- Connected to GitHub repo: `codezxz/flask-user-api`
- Uses `render.yaml` for configuration
- Auto-deployed at: `https://flask-user-api.onrender.com` (after Render setup)

## 👨‍💻 Author

**codezxz** - [GitHub](https://github.com/codezxz)
