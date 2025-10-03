# Swipe-Interview-Assistant
Swipe Interview Assistant is a React-based AI-powered interview platform. Candidates upload resumes (PDF/DOCX), missing details are collected via chatbot, and AI conducts a timed full-stack interview. Interviewers view scores, profiles, chat history, and summaries. Progress persists locally with pause/resume support.

# 🌟 Swipe Interview Assistant
<img src="./screenshots/chat.png" alt="Interviewee Chat" width="200" />
<img src="./screenshots/dashboard.png" alt="Interviewer Dashboard" width="200" />
<img src="./screenshots/resume-upload.png" alt="Resume Upload" width="200" />
<img src="./screenshots/ai-summary.png" alt="AI Summary" width="200" />

[![License: MIT](https://img.shields.io/badge/License-MIT-blue.svg)](LICENSE)  
[![React](https://img.shields.io/badge/React-17.0.2-blue.svg)](https://reactjs.org/)  
[![JavaScript](https://img.shields.io/badge/JavaScript-ES6-yellow.svg)](https://developer.mozilla.org/en-US/docs/Web/JavaScript)  

Swipe Interview Assistant is a **React-based AI-powered platform** that simulates real-world interviews. Candidates can upload resumes, fill missing details, and take timed AI-generated interviews. Interviewers can track performance, view chat history, and analyze AI summaries.

---

## 🚀 Features

### 🎯 Interviewee (Chat)
- Upload **resume (PDF/DOCX)**
- Auto-extract **Name, Email, Phone**; chatbot collects missing fields
- AI conducts **timed interviews** with 6 questions (Easy → Medium → Hard)
- Answers are **automatically scored**

### 🧑‍💼 Interviewer (Dashboard)
- View **candidates ordered by score**
- Access **chat history, profile, and AI-generated summary**
- Supports **pause/resume** with a “Welcome Back” modal

### 💾 Persistence
- All data stored **locally** to retain progress after closing/reopening the app

---

## 🛠️ Tech Stack
- **Frontend:** React.js  
- **AI Integration:** [Specify your AI service, e.g., OpenAI/Claude]  
- **State Management:** React State + LocalStorage  
- **Styling:** CSS / Styled Components  

---

## ⚡ Installation

```bash
# Clone the repository
git clone <repo-url>
cd swipe-interview-assistant

# Install dependencies
npm install

# Run the app
npm start
