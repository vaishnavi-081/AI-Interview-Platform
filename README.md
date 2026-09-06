# 🤖 AI Technical Interview Platform

> An AI-powered technical interview and coding assessment platform that enables organizations to conduct structured, interactive, and intelligent candidate evaluations.

![React](https://img.shields.io/badge/React-19-61DAFB?logo=react&logoColor=white)
![Vite](https://img.shields.io/badge/Vite-7-646CFF?logo=vite&logoColor=white)
![Node.js](https://img.shields.io/badge/Node.js-20+-339933?logo=node.js&logoColor=white)
![Express](https://img.shields.io/badge/Express.js-5-000000?logo=express&logoColor=white)
![MongoDB](https://img.shields.io/badge/MongoDB-Database-47A248?logo=mongodb&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-ES6+-F7DF1E?logo=javascript&logoColor=black)
![AI](https://img.shields.io/badge/AI-Powered-purple)

---

## 📌 Overview

The **AI Technical Interview Platform** is a full-stack web application designed to streamline the technical recruitment process.

The platform combines AI-assisted interviewing, coding assessments, candidate monitoring, interview scheduling, and recruiter workflows into a centralized system.

It is designed to reduce manual screening effort while providing structured and data-driven candidate evaluation.

---

## 🎯 Problem Statement

Traditional technical recruitment processes often require:

- Manual resume screening
- Repetitive technical interviews
- Separate coding assessment platforms
- Manual candidate evaluation
- Complex interview scheduling
- Limited candidate performance insights

This platform addresses these challenges by providing an integrated environment for **technical interviews, coding assessments, candidate monitoring, and recruiter management**.

---

## ✨ Key Features

### 👨‍💻 Candidate Portal

- Candidate registration and login
- Interview setup
- Technical interview sessions
- AI-assisted interview interaction
- Coding assessments
- Project/code submission
- Interview session tracking
- Candidate performance evaluation

### 🤖 AI-Powered Interviewing

- AI-assisted technical questioning
- Dynamic interview sessions
- Candidate response analysis
- Automated evaluation workflows
- Intelligent interview experience

### 💻 Coding Assessment

- Online coding environment
- Technical coding challenges
- Candidate code submission
- AI-assisted code analysis
- Coding performance evaluation

### 🎥 Interview Monitoring

- Camera-based candidate monitoring
- Face detection
- Object detection
- Interview environment monitoring
- Real-time monitoring interface

### 📅 Interview Scheduling

- Interview scheduling
- Session management
- Candidate scheduling
- Recruiter interview management

### 🧑‍💼 Recruiter Dashboard

- Candidate management
- Candidate shortlisting
- Interview scheduling
- Candidate evaluation
- Interview session monitoring
- Recruitment workflow management

### 📊 Candidate Evaluation

- Interview performance
- Coding performance
- AI-generated insights
- Candidate assessment
- Structured evaluation workflow

---

## 🏗️ System Architecture

```text
                    ┌──────────────────────┐
                    │      Candidate       │
                    │   /    Recruiter     │
                    └──────────┬───────────┘
                               │
                               ▼
                    ┌──────────────────────┐
                    │      React + Vite    │
                    │      Frontend        │
                    └──────────┬───────────┘
                               │
                          REST APIs
                               │
                               ▼
                    ┌──────────────────────┐
                    │   Node.js + Express  │
                    │       Backend        │
                    └──────────┬───────────┘
                               │
                  ┌────────────┼────────────┐
                  ▼            ▼            ▼
             ┌─────────┐ ┌──────────┐ ┌───────────┐
             │ MongoDB │ │ AI APIs  │ │ Monitoring│
             │         │ │          │ │ Services  │
             └─────────┘ └──────────┘ └───────────┘
🛠️ Technology Stack
Frontend
React
Vite
JavaScript
Tailwind CSS
ESLint
Backend
Node.js
Express.js
MongoDB
REST APIs
AI & Computer Vision
AI-powered interview workflows
TensorFlow.js
MediaPipe
Face detection
Object detection
AI-assisted code analysis
Tools
Git
GitHub
npm
VS Code
📂 Project Structure
AI-Interview-Platform/
│
├── backend/
│   ├── models/
│   ├── routes/
│   ├── utils/
│   ├── server.js
│   └── package.json
│
├── frontend/
│   ├── public/
│   ├── src/
│   │   ├── components/
│   │   ├── pages/
│   │   ├── App.jsx
│   │   └── main.jsx
│   ├── package.json
│   └── vite.config.js
│
├── Images/
│
├── README.md
└── LICENSE
🚀 Getting Started
Prerequisites

Make sure you have installed:

Node.js 20+
npm
MongoDB
Git
1. Clone the repository
git clone https://github.com/vaishnavi-081/AI-Interview-Platform.git
cd AI-Interview-Platform
2. Setup Backend
cd backend
npm install

Create your environment file:

cp .env.example .env

Configure the required environment variables.

Start the backend:

npm start
3. Setup Frontend

Open another terminal:

cd frontend
npm install
npm run dev

The application will be available at:

http://localhost:5173
🔐 Environment Configuration

Example:

PORT=5000
MONGO_URI=your_mongodb_connection_string
JWT_SECRET=your_secret_key

Never commit real API keys, passwords, database credentials, or other secrets to GitHub.

🔄 Application Workflow
Candidate
   │
   ▼
Registration / Login
   │
   ▼
Interview Setup
   │
   ▼
Technical Interview
   │
   ├──────────────► AI Evaluation
   │
   ├──────────────► Coding Assessment
   │
   └──────────────► Candidate Monitoring
   │
   ▼
Performance Analysis
   │
   ▼
Recruiter Dashboard
   │
   ▼
Candidate Shortlisting
📈 Future Enhancements
Advanced LLM-based interview generation
Multi-language coding execution
Advanced anti-cheating mechanisms
Resume-to-interview personalization
Candidate skill-gap analysis
Advanced recruiter analytics
Automated interview reports
Email and calendar integrations
Cloud deployment
Microservice architecture
🔒 Security Considerations

The application should be deployed in production with:

Secure authentication
Strong password policies
Protected API endpoints
Environment-based secrets
HTTPS
Input validation
Rate limiting
Restricted CORS configuration
Secure database credentials
💡 Project Highlights

This project demonstrates practical experience with:

Full-stack web development
REST API development
Database integration
AI integration
Computer vision
Candidate assessment workflows
Recruitment automation
Frontend component architecture
Backend API design
👩‍💻 Developer
Vaishnavi Revanuru

Computer Science & Engineering Student

Areas of Interest

Full-Stack Development
Artificial Intelligence
Machine Learning
Software Engineering
Cloud Technologies

GitHub:
https://github.com/vaishnavi-081
