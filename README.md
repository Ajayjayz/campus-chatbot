# 🎓 AI Campus Chatbot

An intelligent AI-powered Campus Chatbot built using [Rasa](https://rasa.com/) for the backend and React.js for the frontend. It answers college-related queries like admissions, fees, courses, hostel, transport, and more.

---

## 💡 Features

- Natural conversation flow using Rasa NLU + stories/rules
- Typing animation for bot replies
- Bot avatar for a friendly UI
- Chat history is saved in the browser
- Handles fuzzy inputs like `"btch"`, `"i want mba"`, etc.
- 15+ intents: `admission_info`, `btech_courses`, `mba_courses`, `hostel`, `placements`, `fees`, and more.

---

## 📁 Project Structure

campus-chatbot-project/
│
├── rasa_bot/ ← Rasa backend
│ ├── domain.yml
│ ├── data/
│ └── ...
│
└── frontend/ ← React frontend
├── src/App.js
├── src/App.css
└── ...

---

## 🚀 Getting Started

### 🧠 Rasa Backend

```bash
cd rasa_bot
rasa train
rasa run
```
```bash
cd frontend
npm install
npm start
```

### 📦 Backend (Rasa)

1. **Navigate to backend folder**:
   ```bash
   cd rasa_bot
   ```
python -m venv rasaenv
rasaenv\Scripts\activate    # On Windows
pip install -r requirements.txt
rasa train
rasa run --enable-api


📚 Credits
Developed by Ajay


---

Let me know if you want me to **generate the full `README.md` file** and save it inside your project too.
