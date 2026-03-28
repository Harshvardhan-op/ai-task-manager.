🚀 AI Task Manager (Rule-Based AI)

A full-stack task management web application built using Flask (Backend) and React (Frontend) with a rule-based AI system for task prioritization.
This project enables users to efficiently manage tasks and receive intelligent suggestions based on task content.

---
📌 Features

- ✅ Create, view, update, and delete tasks (CRUD)
- 📊 Task priority management (High / Medium / Low)
- 🔄 Toggle task status (Pending / Completed)
- 🤖 AI-based task suggestions using rule-based logic
- 🎨 Clean and responsive user interface
- ⚡ Fast and lightweight Flask backend

---

🛠️ Tech Stack

🔹 Frontend

- React (Vite)
- JavaScript
- CSS

🔹 Backend

- Python (Flask)
- Flask-SQLAlchemy
- SQLite Database

---

📂 Project Architecture

AI-Task-Manager/
│
├── Backend/
│   ├── app/
│   │   ├── __init__.py
│   │   ├── models.py
│   │   ├── config.py
│   │   └── routes/
│   │       └── tasks.py
│   │
│   ├── run.py
│   └── requirements.txt
│
├── Frontend/
│   ├── src/
│   │   ├── App.jsx
│   │   ├── main.jsx
│   │   └── index.css
│   │
│   ├── index.html
│   └── package.json
│
└── README.md

---

⚙️ How to Run the Project

🔹 Backend Setup

cd Backend
python -m venv venv
venv\Scripts\activate   # Windows
pip install -r requirements.txt
python run.py

📍 Backend runs at:
http://127.0.0.1:5000

---

🔹 Frontend Setup

cd Frontend
npm install
npm run dev

📍 Frontend runs at:
http://localhost:5173

---

🔗 API Endpoints

Method| Endpoint| Description
GET| /api/tasks| Get all tasks
POST| /api/tasks| Create a task
PUT| /api/tasks/<id>| Update a task
DELETE| /api/tasks/<id>| Delete a task
POST| /api/tasks/<id>/ai-suggest| Get AI suggestion

---

🤖 AI Feature (Rule-Based)

The application uses a rule-based AI system to analyze task titles and generate:

- Priority suggestions (High / Medium / Low)
- Short actionable recommendations

🔍 Example Logic

- “urgent”, “deadline” → High Priority
- “later”, “optional” → Low Priority
- Other tasks → Medium Priority

✅ Benefits

- No external API required
- Zero cost
- Reliable and fast performance

---

🎯 Use Cases

- Personal task management
- Productivity enhancement
- Academic project demonstration
- Full-stack development practice

---

🧠 Learning Outcomes

- Full-stack development (React + Flask)
- REST API design and integration
- Database management using SQLAlchemy
- State management in React
- Rule-based AI implementation

---

📌 Future Improvements

- User authentication (Login/Signup)
- Task reminders and notifications
- Drag-and-drop task management
- Dark mode UI
- Advanced AI integration

---

👨‍💻 Author

Developed by Harshvardhan Rathore

---

⭐ Conclusion

This project demonstrates a complete full-stack application with a rule-based AI system, making it efficient, reliable, and suitable for both academic and portfolio purposes.

---
