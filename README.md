# 📝 Task Manager (Full-Stack Project)

A simple full-stack Task Manager application built with a Node.js/Express backend and a React frontend.  
Users can create, edit, delete, and mark tasks as completed.  
This project demonstrates full-stack CRUD development, clean API design, and component-based UI structure.

---

## 🚀 Features

- Create new tasks  
- Edit existing tasks  
- Delete tasks  
- Mark tasks as completed  
- Clear all completed tasks  
- Responsive React UI  
- RESTful API with Express  
- Modular folder structure  

---

## 🛠 Tech Stack

### **Frontend**
- React  
- Vite  
- JavaScript  
- CSS  

### **Backend**
- Node.js  
- Express  
- CORS  
- Nodemon (dev)

---

## 📂 Project Structure

TaskManager/
│
├── backend/
│   ├── package.json
│   ├── server.js
│   ├── routes/tasks.js
│   ├── models/tasks.js
│   └── data/tasks.json
│
└── frontend/
    ├── package.json
    ├── vite.config.js
    ├── index.html
    └── src/
        ├── App.jsx
        ├── main.jsx
        ├── components/
        │   ├── TaskList.jsx
        │   ├── TaskItem.jsx
        │   └── TaskForm.jsx
        └── styles/
            └── main.css

---

## ⚙️ Backend Setup

```
cd backend
npm install
npm start
```

Runs on:  
`http://localhost:5000`

---

## 💻 Frontend Setup

```
cd frontend
npm install
npm run dev
```

Runs on:  
`http://localhost:5173`

---

## 🔌 API Endpoints

| Method | Endpoint        | Description              |
|--------|----------------|--------------------------|
| GET    | `/tasks`       | Get all tasks            |
| POST   | `/tasks`       | Create a new task        |
| PUT    | `/tasks/:id`   | Update a task            |
| DELETE | `/tasks/:id`   | Delete a task            |
| DELETE | `/tasks`       | Delete all completed     |

---

## 🎯 Future Improvements

- User authentication (JWT)  
- Move to real database (MongoDB / PostgreSQL)  
- Drag-and-drop task sorting  
- Light/dark mode  

---

## 📘 About This Project

This project demonstrates practical full-stack engineering skills including backend API development, UI component architecture, and client–server integration.
