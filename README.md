# 🌟 Swipe Interview Assistant

[![License: MIT](https://img.shields.io/badge/License-MIT-blue.svg)](LICENSE)  
[![React](https://img.shields.io/badge/React-17.0.2-blue.svg)](https://reactjs.org/)  
[![JavaScript](https://img.shields.io/badge/JavaScript-ES6-yellow.svg)](https://developer.mozilla.org/en-US/docs/Web/JavaScript)  

Swipe Interview Assistant is a **React-based AI-powered interview platform**. Candidates upload resumes, fill missing details, and take timed AI-generated interviews. Interviewers track performance, view chat history, and analyze AI summaries. All data persists locally with pause/resume support.

---

## 📸 Screenshots

<div style="display: flex; gap: 10px; flex-wrap: wrap;">

<img src="./screenshot/Screenshot%202025-10-03%20171730.png" alt="Interviewee Chat" width="250" />
<img src="./screenshot/Screenshot%202025-10-03%20171757.png" alt="Interviewer Dashboard" width="250" />
<img src="./screenshot/Screenshot%202025-10-03%20171811.png" alt="Resume Upload" width="250" />

</div>


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
- **AI Integration:** [Specify AI service, e.g., OpenAI/Claude]  
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
