# Kaizen 🇯🇵

## AI-Powered Japanese Learning Platform

Kaizen is an AI-powered Japanese learning platform that combines language learning, conversational AI, gamification, and anime-inspired learning into one modern SaaS-style application.

Built completely using FREE and open-source technologies.

---

# ✨ Features

## 📚 Japanese Learning

### Hiragana & Katakana Practice

* Flashcards
* Quizzes
* Writing practice
* Typing practice

### Vocabulary Learning

* JLPT N5/N4 vocabulary
* Spaced repetition system (SRS)
* Example sentences
* Pronunciation support

### Grammar Lessons

* Interactive explanations
* Sentence breakdowns
* Particle explanations
* Practice quizzes

---

# 🤖 AI Features

## AI Sensei Chatbot

Practice Japanese conversations with an AI tutor.

### Features

* Ask grammar doubts
* Practice conversations
* Sentence correction
* Natural Japanese responses

---

## AI Sentence Explainer

Enter a Japanese sentence and Kaizen explains:

### Example

Input:

```txt
私は学生です
```

Output:

```txt
私 = I
は = topic particle
学生 = student
です = polite form of “to be”
```

---

## 🎤 Pronunciation Checker

* Speech recognition
* Pronunciation scoring
* Improvement suggestions

---

## 🎌 Anime Japanese Mode

Learn Japanese through anime phrases and subtitle explanations.

### Features

* Anime dialogues
* Slang explanations
* Casual vs formal Japanese
* Subtitle learning

---

# 🎮 Gamification

Kaizen includes a Duolingo-inspired progression system.

### Features

* XP system
* Levels
* Daily streaks
* Achievements
* Badges
* Daily quests

---

# 🛠 Tech Stack

## Frontend

* React
* Vite
* Tailwind CSS
* React Router
* Axios

## Backend

* FastAPI
* Python
* SQLAlchemy

## Database

* PostgreSQL (Supabase Free Tier)

## AI & NLP

* Ollama
* Gemma / Mistral / Llama 3
* transformers
* sentence-transformers
* fugashi
* MeCab

## Speech Recognition

* Browser Speech API
* Whisper.cpp

---

# 💻 Project Structure

```txt
kaizen/
│
├── frontend/
│   ├── src/
│   ├── components/
│   ├── pages/
│   ├── services/
│   └── assets/
│
├── backend/
│   ├── app/
│   ├── routes/
│   ├── models/
│   ├── ai/
│   └── database/
│
├── datasets/
│
└── README.md
```

---

# 🚀 Getting Started

## 1. Clone Repository

```bash
git clone https://github.com/your-username/kaizen.git
cd kaizen
```

---

# Frontend Setup

## Install Dependencies

```bash
cd frontend
npm install
```

## Start Frontend

```bash
npm run dev
```

---

# Backend Setup

## Create Virtual Environment

```bash
cd backend
python -m venv venv
```

## Activate Environment

### Windows

```bash
venv\Scripts\activate
```

---

## Install Dependencies

```bash
pip install fastapi uvicorn sqlalchemy psycopg2-binary python-dotenv ollama fugashi unidic-lite
```

## Start Backend

```bash
uvicorn main:app --reload
```

---

# 🤖 Install Ollama

Download Ollama:

[https://ollama.com](https://ollama.com)

Run local AI model:

```bash
ollama run gemma:2b
```

---

# 📈 MVP Features

Initial version includes:

* Authentication
* Hiragana practice
* Vocabulary flashcards
* XP system
* Daily streaks
* AI sentence explainer
* AI chatbot

---

# 🔥 Future Features

* AI voice tutor
* Kanji recognition
* Anime subtitle parsing
* Multiplayer learning
* AI-generated quizzes
* Mobile app
* Personalized AI learning paths

---

# 🎯 Goals

Kaizen aims to become:

* an AI Japanese tutor
* a gamified language learning platform
* a startup-level educational SaaS product

---

# 🧠 Why This Project Stands Out

Kaizen demonstrates:

* Full-stack development
* AI integration
* NLP systems
* Speech processing
* Gamification systems
* SaaS product architecture
* UI/UX engineering

---

# 📄 Resume Description

Developed an AI-powered Japanese learning platform using React, FastAPI, PostgreSQL, and local LLMs featuring conversational AI practice, grammar explanations, vocabulary quizzes, streak tracking, and gamified learning.

---

# 📌 Status

🚧 Currently in development.

---

# 👨‍💻 Author

Built with passion for AI, Japanese learning, and product development.
