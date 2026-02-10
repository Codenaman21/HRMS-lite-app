🧑‍💼 HRMS Lite – Employee & Attendance Management System
=========================================================

HRMS Lite is a lightweight **Human Resource Management System** built with **FastAPI (Backend)** and **React (Frontend)**.It allows you to manage employees and track attendance using a simple dashboard and REST APIs.

🚀 Features
-----------

*   👤 Employee Management (Add, List, Delete)
    
*   🕒 Attendance Management
    
*   ⚡ FastAPI backend with Swagger API docs
    
*   🌐 React frontend dashboard
    
*   📦 SQLite database for easy setup
    
*   🔗 REST API integration using Axios
    
*   ☁️ Deployed Backend on Render and Frontend on Vercel
    

🛠️ Tech Stack
--------------

### Backend

*   FastAPI
    
*   SQLAlchemy
    
*   SQLite
    
*   Uvicorn
    

### Frontend

*   React
    
*   Axios
    
*   CSS / Tailwind (if used)
    

📁 Project Structure
--------------------

```text
HRMS-lite-app/
├── backend/
│   ├── main.py            # Entry point
│   ├── database.py        # DB connection logic
│   ├── models.py          # SQLAlchemy models
│   ├── routers/           # API routes
│   └── requirements.txt   # Backend dependencies
│
├── frontend/
│   ├── src/               # React components & logic
│   ├── public/            # Static assets
│   └── package.json       # Frontend dependencies
│
└── README.md
```


---

## ⚙️ Setup Instructions

### 1️⃣ Clone the Repository
```bash
git clone [https://github.com/Codenaman21/HRMS-lite-app.git](https://github.com/Codenaman21/HRMS-lite-app.git)
cd HRMS-lite-app
```

### 2️⃣ Backend Setup

```bash
cd backend
python -m venv venv
venv\Scripts\activate   # On Windows
# source venv/bin/activate   # On Mac/Linux

pip install -r requirements.txt
uvicorn main:app --reload
```

Backend will run at:

http://127.0.0.1:8000

Swagger API Docs:

http://127.0.0.1:8000/docs

### 3️⃣ Frontend Setup

```bash
cd frontend
npm install
npm run dev
```

Frontend will run at:

http://localhost:5173

(or similar port depending on your setup)


🔗 API Endpoints
---------------------------

### Employees

*   GET /employees/ → Get all employees
    
*   POST /employees/ → Add new employee
    
*   DELETE /employees/{id} → Delete employee
    

### Attendance

*   POST /attendance/ → Mark attendance
    
*   GET /attendance/{employee\_id} → Get attendance for an employee

    

📜 License
----------

This project is Under MIT License and intended for **educational and demo purposes**.
