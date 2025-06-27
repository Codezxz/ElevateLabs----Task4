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
git clone https://github.com/codezxz/.git
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


## User Management API Endpoints

Method	Endpoint	Description	Parameters	Request Body Required

GET	/users	Retrieve all users	None	❌ No
GET	/users/<user_id>	Retrieve a user by ID	user_id (int)	❌ No
POST	/users	Create a new user	None	✅ Yes (name, email)
PUT	/users/<user_id>	Update an existing user	user_id (int)	✅ Yes (partial or full)
DELETE	/users/<user_id>	Delete a user by ID	user_id (int)	❌ No

## API Endpoints: http://localhost:5000/apidocs

## 👨‍💻 Author

**codezxz** - [GitHub](https://github.com/codezxz)
