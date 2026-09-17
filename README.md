# Student Management System - Full-Stack CRUD Web Application

## 📋 Overview
A complete full-stack CRUD (Create, Read, Update, Delete) web application developed as part of **VSB Skill Vault – Activity 3**. This project demonstrates full-stack web application architecture by connecting a responsive client-side interface to a robust backend REST API and a relational database.

---

## 🛠️ Technology Stack
* **Frontend:** HTML5, CSS3, JavaScript (Fetch API for asynchronous backend communication)
* **Backend:** Python, Django, Django REST Framework (DRF)
* **CORS Management:** `django-cors-headers` for seamless cross-origin integration
* **Database:** SQLite (Relational database management)
* **Version Control:** Git & GitHub

---

## 🚀 Key Features & CRUD Implementation
* **Create (POST):** Add new student records including full name, email, and course details through an interactive web form.
* **Read (GET):** Dynamically fetch and display all saved student records in a structured table layout.
* **Update / Delete (DELETE/PUT):** Manage existing records seamlessly with real-time UI updates upon database modification.
* **Server-Side & Client-Side Validation:** Ensures required fields and proper data formatting are enforced.

---

## 🔌 REST API Endpoints

| Operation | HTTP Method | Endpoint | Description |
| :--- | :--- | :--- | :--- |
| **Read All** | `GET` | `/api/students/` | Retrieve a list of all student records |
| **Create** | `POST` | `/api/students/` | Add a new student record |
| **Read One**| `GET` | `/api/students/{id}/` | Retrieve a specific student by ID |
| **Update** | `PUT/PATCH` | `/api/students/{id}/` | Update an existing student record |
| **Delete** | `DELETE` | `/api/students/{id}/` | Remove a student record from the database |

---

## ⚙️ Installation & Local Execution Steps

### 1. Clone the Repository
```bash
git clone [https://github.com/johnjoshwa-tech/student-management-crud.git](https://github.com/johnjoshwa-tech/student-management-crud.git)
cd student-management-crud/student_project
