# 📝 Todo App — Django REST API + Frontend

A simple, clean, and fully functional **Todo Application** built using **Django**, **Django REST Framework**, and a minimal **HTML/CSS/JS frontend**.
This project demonstrates how to build a complete CRUD-based Todo system using REST APIs.

---

## 🚀 Features

### **Backend (Django + DRF)**

* ✔ Create tasks
* ✔ Read task list
* ✔ Update tasks (edit + mark complete / incomplete)
* ✔ Delete tasks
* ✔ JSON-based REST API
* ✔ CSRF secure endpoints
* ✔ Clean serializers + views + URLs

### **Frontend**

* ✔ Modern UI
* ✔ Dark/Light mode
* ✔ Fully responsive
* ✔ Ajax-based API calls (No page reload)
* ✔ Smooth UX

---

## 📁 Project Structure

```
TodoP/
│── todo_drf/
│   ├── api/
│   │   ├── models.py
│   │   ├── serializers.py
│   │   ├── urls.py
│   │   ├── views.py
│   ├── settings.py
│   ├── urls.py
│── templates/
│   ├── index.html
│── static/
│   ├── css/
│   ├── js/
│── manage.py
```

---

## 🔧 Tech Stack

### **Backend**

* Python
* Django
* Django REST Framework

### **Frontend**

* HTML
* CSS
* Vanilla JavaScript (Fetch API)

---

## 📦 Installation & Setup

### 1️⃣ Clone the repository

```bash
git clone https://github.com/your-username/Todo_app.git
cd Todo_app
```

### 2️⃣ Create a virtual environment

```bash
python -m venv venv
```

### 3️⃣ Activate it

**Windows**

```bash
venv\Scripts\activate
```

**Mac/Linux**

```bash
source venv/bin/activate
```

### 4️⃣ Install dependencies

```bash
pip install -r requirements.txt
```

### 5️⃣ Run the server

```bash
python manage.py runserver
```

Open the project at:
👉 [http://127.0.0.1:8000/](http://127.0.0.1:8000/)

---

## 🧪 API Endpoints (DRF)

| Method | Endpoint                 | Description       |
| ------ | ------------------------ | ----------------- |
| GET    | `/api/task-list/`        | Get all tasks     |
| GET    | `/api/task-detail/<id>/` | Get specific task |
| POST   | `/api/task-create/`      | Create a new task |
| POST   | `/api/task-update/<id>/` | Update a task     |
| DELETE | `/api/task-delete/<id>/` | Delete a task     |

---

## 🎯 Purpose of the Project

This project is ideal for:

* Learning **REST API development** with Django
* Understanding CRUD operations
* Connecting frontend with backend using Fetch API
* Beginners entering backend/web development

---

## 📌 Future Improvements

* User authentication
* JWT tokens
* Pagination
* Category-based tasks
* React / Vue frontend

---

## 🤝 Contributing

Feel free to submit issues or pull requests to improve the project!

---

## 📜 License

This project is open-source under the **MIT License**.

