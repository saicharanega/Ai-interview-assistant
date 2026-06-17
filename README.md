# 🎤 AI Interview Assistant

An AI-powered interview preparation platform that simulates real interview experiences through voice interaction, adaptive questioning, and personalized feedback.

## 🚀 Live Demo

🌐 Frontend: https://ai-interview-assistant-one-kappa.vercel.app

## ✨ Features

* 🎙️ Voice-based interview experience
* 🤖 AI Interviewer (Natalie)
* 📚 Multiple Interview Domains

  * Self Introduction
  * Generative AI
  * Python
  * English
  * HTML
  * CSS
* 🗣️ Speech-to-Text using AssemblyAI
* 🔊 Real-time AI Voice Responses using Murf AI
* 🧠 Adaptive Question Generation powered by Groq LLM
* 📊 Automated Interview Feedback & Scoring
* ⏱️ Live Interview Timer
* 🌐 Fully Deployed Cloud Application

---

## 🛠️ Tech Stack

### Frontend

* HTML5
* CSS3
* JavaScript
* Tailwind CSS

### Backend

* Python
* Flask
* Flask-CORS

### AI & APIs

* Groq LLM
* Murf AI
* AssemblyAI
* LangChain
* LangGraph

### Deployment

* Vercel (Frontend)
* Render (Backend)
* GitHub

---

## 📂 Project Structure

```text
AI-Interview-Assistant/
│
├── frontend/
│   ├── index.html
│   ├── index.js
│   └── styles.css
│
├── backend/
│   ├── app.py
│   ├── requirements.txt
│   └── .env
│
├── screenshots/
│
└── README.md
```

---

## ⚙️ Installation

### Clone Repository

```bash
git clone https://github.com/saicharanega/Ai-interview-assistant.git
cd Ai-interview-assistant
```

### Backend Setup

```bash
cd backend

python -m venv venv

source venv/bin/activate
# Windows:
# venv\Scripts\activate

pip install -r requirements.txt
```

Create a `.env` file:

```env
GOOGLE_API_KEY=your_key
GROQ_API_KEY=your_key
MURF_API_KEY=your_key
ASSEMBLYAI_API_KEY=your_key
```

Run Backend:

```bash
python app.py
```

### Frontend Setup

Open:

```text
frontend/index.html
```

Or deploy using Vercel.

---

## 🎯 How It Works

1. Select an interview topic.
2. Start the interview session.
3. AI interviewer asks a question.
4. Candidate responds using voice.
5. AssemblyAI converts speech to text.
6. Groq LLM generates contextual follow-up questions.
7. Murf AI converts AI responses into speech.
8. After five questions, detailed feedback is generated automatically.

---

## 📸 Screenshots

### Home Screen

![Home Screen](screenshots/Screenshot%202026-06-17%20at%202.47.10%E2%80%AFPM.png)

### Interview Session

![Interview Session](screenshots/Screenshot%202026-06-17%20at%202.47.58%E2%80%AFPM.png)

### AI Speaking Interface

![AI Speaking Interface](screenshots/Screenshot%202026-06-17%20at%202.48.15%E2%80%AFPM.png)

---

## 🔮 Future Improvements

* Resume-based Interview Generation
* Coding Interview Mode
* Video Interview Support
* Interview Analytics Dashboard
* User Authentication
* Interview History Tracking
* Performance Trend Analysis

---

## 👨‍💻 Author

**Sai Charan Ega**

* GitHub: https://github.com/saicharanega
* LinkedIn: https://www.linkedin.com/in/saicharanega

---

## ⭐ Support

If you found this project useful, please consider giving it a ⭐ on GitHub.
