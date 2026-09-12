# Task Management System

A full-stack task management application designed to help users efficiently create, organize, update, and track their tasks through a simple and intuitive interface.

## 🚀 Features

* **Task Management** — Create, view, update, and delete tasks.
* **Task Status Tracking** — Organize tasks based on their current status.
* **Responsive UI** — Access and manage tasks across different screen sizes.
* **Frontend & Backend Architecture** — Separate frontend and backend applications for better scalability and maintainability.
* **REST API Integration** — Frontend communicates with the backend through APIs.
* **Persistent Data** — Store and manage task information through the backend.

## 🛠️ Tech Stack

### Frontend

* React.js
* JavaScript
* HTML5
* CSS3

### Backend

* Node.js
* Express.js
* REST APIs

### Database

* MongoDB

### Development Tools

* Git
* GitHub
* VS Code

## 📁 Project Structure

```text
task-management-system/
│
├── backend/
│   ├── controllers/
│   ├── models/
│   ├── routes/
│   ├── middleware/
│   ├── config/
│   └── server.js
│
├── frontend/
│   ├── src/
│   │   ├── components/
│   │   ├── pages/
│   │   ├── services/
│   │   └── App.js
│   ├── public/
│   └── package.json
│
└── README.md
```

> The exact folder structure may vary depending on the version of the project.

## ⚙️ Installation & Setup

### 1. Clone the repository

```bash
git clone https://github.com/YOUR-USERNAME/task-management-system.git
cd task-management-system
```

### 2. Set up the Backend

Navigate to the backend directory:

```bash
cd backend
```

Install dependencies:

```bash
npm install
```

Create a `.env` file:

```env
PORT=5000
MONGO_URI=your_mongodb_connection_string
```

Start the backend server:

```bash
npm start
```

For development:

```bash
npm run dev
```

### 3. Set up the Frontend

Open another terminal and navigate to the frontend:

```bash
cd frontend
```

Install dependencies:

```bash
npm install
```

Start the development server:

```bash
npm start
```

The application should now be available at:

```text
http://localhost:3000
```

The backend typically runs on:

```text
http://localhost:5000
```

## 🔐 Environment Variables

The backend requires environment variables for configuration.

Example:

```env
PORT=5000
MONGO_URI=your_mongodb_connection_string
```

Do not commit your `.env` file to GitHub.

Make sure `.env` is included in `.gitignore`:

```text
.env
node_modules/
```

## 🔄 Application Flow

```text
User
  │
  ▼
React Frontend
  │
  │ REST API Requests
  ▼
Node.js + Express Backend
  │
  ▼
MongoDB Database
```

Users interact with the frontend to manage tasks. The frontend sends API requests to the Express backend, which processes the requests and stores or retrieves task data from MongoDB.

## 📌 Future Improvements

* User authentication and authorization
* Role-based access control
* Task priority levels
* Task deadlines and reminders
* Search and filtering
* Drag-and-drop task management
* Email notifications
* Dashboard with task statistics
* Deployment using cloud platforms

## 📄 License

This project is intended for educational and development purposes.
