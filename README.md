 Task Manager Pro

A clean and scalable full-stack Task Manager application built to demonstrate strong fundamentals in frontend, backend, and API design.

---

 Live Demo


Frontend: https://your-app.vercel.app
Backend: https://your-api.onrender.com

---

 Overview

This project implements a complete task management system with a focus on:

* Clean architecture and code organization
* RESTful API design
* User experience and responsiveness
* Maintainability and scalability

---

 Tech Stack

Frontend

* React (Vite)
* Axios
* Custom CSS

Backend

* Node.js
* Express

Storage

* In-memory (as per assignment scope)
* LocalStorage (for frontend persistence)

---

 Features

 Core Requirements

* Create new tasks
* View all tasks
* Mark tasks as completed
* Delete tasks
* Loading and error handling
* Input validation

 Enhancements (Bonus)

* Edit task title
* Filter tasks (All / Completed / Pending)
* Local persistence using LocalStorage
* Clean, modern UI

---

 API Endpoints

| Method | Endpoint   | Description               |
| ------ | ---------- | ------------------------- |
| GET    | /tasks     | Fetch all tasks           |
| POST   | /tasks     | Create a new task         |
| PATCH  | /tasks/:id | Update task (toggle/edit) |
| DELETE | /tasks/:id | Delete task               |

---

 Project Structure

```
task-manager-pro/
│
├── backend/        # Express API
├── frontend/       # React application
└── README.md
```

---

 Setup Instructions

 1. Clone Repository

```bash
git clone https://github.com/YOUR_USERNAME/task-manager-pro.git
cd task-manager-pro
```

---

 2. Run Backend

```bash
cd backend
npm install
npm start
```

Server runs on: http://localhost:5000

---

 3. Run Frontend

```bash
cd frontend
npm install
npm run dev
```

Frontend runs on: http://localhost:5173

---

 Design Decisions

* Used in-memory storage to keep implementation simple and aligned with assignment scope
* Focused on functionality over heavy UI design
* Added LocalStorage persistence to improve user experience
* Maintained clean and minimal REST API structure

---

 Future Improvements

* Database integration (MongoDB / PostgreSQL)
* Authentication and user accounts
* Drag-and-drop task management
* Unit and integration testing
* Docker containerization

---

 Submission Note

This implementation fulfills all core requirements and includes additional enhancements such as task editing, filtering, and persistence to demonstrate scalability, usability, and thoughtful product design.

---

 Author

Debanjan Karmakar
