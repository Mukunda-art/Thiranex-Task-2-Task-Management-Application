# 📌 Task Management Application

A simple and responsive **Task Management Web Application** developed using **HTML, CSS, JavaScript, Node.js, and Express.js**.

This application helps users manage daily tasks efficiently with features such as task creation, viewing, deletion, and user login.

---

## 🚀 Features

✅ User Login Authentication
✅ Create New Tasks
✅ View Task List
✅ Delete Existing Tasks
✅ Responsive User Interface
✅ Backend API Integration

---

## 🛠️ Technologies Used

### Frontend

* HTML5
* CSS3
* JavaScript

### Backend

* Node.js
* Express.js
* CORS

---

## 📂 Project Structure

```plaintext
Task-Management-App/
│
├── backend/
│   └── server.js
│
├── frontend/
│   ├── index.html
│   ├── style.css
│   └── script.js
│
├── package.json
└── README.md
```

---

## ⚙️ Installation & Setup

### Clone Repository

```bash
git clone https://github.com/j.mukunda/task-management-app.git
```

### Open Project Folder

```bash
cd task-management-app
```

### Install Dependencies

```bash
npm install
```

### Start Backend Server

```bash
node server.js
```

Backend will run at:

```plaintext
http://localhost:5000
```

---

## ▶️ Run Frontend

Open:

```plaintext
frontend/index.html
```

Or use Live Server:

```bash
npx live-server
```

Open browser:

```plaintext
http://127.0.0.1:8080
```

---

## 📡 API Endpoints

### Home Route

```http
GET /
```

Response:

```json
Task Management Backend Running 🚀
```

---

### Get Tasks

```http
GET /tasks
```

Returns all available tasks.

---

### Create Task

```http
POST /tasks
```

Body:

```json
{
"title":"Complete Project",
"description":"Build Task App",
"priority":"High"
}
```

---

### Delete Task

```http
DELETE /tasks/:id
```

Deletes selected task.

---

### Login

```http
POST /login
```

Body:

```json
{
"email":"admin@gmail.com",
"password":"123456"
}
```

---

## 🔮 Future Improvements

* Edit Task Feature
* User Registration
* MongoDB Database Integration
* JWT Authentication
* Task Status Tracking
* Search and Filter Tasks

---

## 👨‍💻 Author

Developed by **J. Mukunda**
