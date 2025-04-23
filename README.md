# 🎓 AcademiaManager

**AcademiaManager** is a full-stack course management system developed using **React.js**, **Spring Boot**, and **Docker**. It offers a responsive frontend and a powerful backend, connected via RESTful APIs with proper CORS configuration. Containerized using Docker Compose, the project is easy to deploy and maintain.

---
## 📸 Screenshots

### 📋 Home
![image](https://github.com/user-attachments/assets/a99bded8-1737-4568-810a-eacbf0461f46)


### ➕ Add Course
![image](https://github.com/user-attachments/assets/b734f581-a600-416e-a921-e7ac0f25424d)
![image](https://github.com/user-attachments/assets/bf560775-17cf-4039-b02b-11808e05235e)
![image](https://github.com/user-attachments/assets/85d7c962-702b-42f9-b68e-324cba61ccbf)
![image](https://github.com/user-attachments/assets/3a2a333a-e749-4555-821b-4fc9073e6d5f)

---
## 🛠️ Tech Stack

- **Frontend:** React.js
- **Backend:** Spring Boot (Java)
- **Database:** H2 (in-memory)
- **Containerization:** Docker, Docker Compose
- **APIs:** RESTful with CORS support

---

## 🚀 Features

- Manage courses through a user-friendly interface
- Full CRUD operations for course data
- Secure backend APIs with CORS handling
- Fully responsive frontend using React components
- Containerized app with Docker Compose for quick setup

---

## 📦 Installation & Setup

### 1. Clone the repository

```bash
git clone https://github.com/your-username/academiamanager.git
cd academiamanager

```

### 2. Run using Docker Compose

Make sure Docker is installed and running on your machine.

```bash
docker-compose up --build
```

The backend will be available at: `http://localhost:8080`  
The frontend will be available at: `http://localhost:3000`

---

## 🧪 API Endpoints

Base URL: `http://localhost:8080/api`

- `GET /courses` – Fetch all courses
- `POST /courses` – Add a new course
- `PUT /courses/{id}` – Update course
- `DELETE /courses/{id}` – Delete course

---

## 📂 Project Structure

```
academiamanager/
├── backend/                      # Spring Boot application
│   ├── src/
│   └── Dockerfile
├── frontend/                     # React.js application
│   ├── src/
│   └── Dockerfile
├── docker-compose.yml
└── README.md
```

---
