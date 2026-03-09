
# 🎓 EduExam Pro – Secure Examination Portal

A modern, secure web-based examination system designed for academic mock tests,
student assessments, and institutional evaluations.

EduExam Pro provides authentication, anti-cheating protection, instant scoring,
and result analytics using a lightweight frontend and Google Apps Script backend.

---

## 📌 Project Overview

EduExam Pro allows institutions to conduct secure online examinations with:

- Secure login authentication
- Login attempt limit protection
- Anti-tab switching monitoring
- Instant result generation
- Student response review
- Admin dashboard

The system can be easily deployed using **GitHub Pages + Google Apps Script**.

---

## 🚀 Key Features

### 🔐 Secure Authentication
- Institutional Email / Student ID login
- Password verification
- Login attempt protection

### 🚫 Anti-Cheating Mechanism
- Tab switching detection
- Attempt blocking
- Proctoring alerts

### 📝 Examination System
- Multiple-choice questions
- Timer-based exam session
- Auto submission

### 📊 Instant Evaluation
- Automatic scoring
- Immediate result display
- Performance tracking

### 📋 Response Review
Students can review:
- Attempted questions
- Correct answers
- Score breakdown

### 👨‍💼 Admin Panel
Admin can:
- Monitor students
- View exam results
- Manage exam sessions

---

## 🏗 System Architecture

Student Browser  
↓  
Frontend (HTML + CSS + JavaScript)  
↓  
Google Apps Script API  
↓  
Google Sheets Database  

---

## 💻 Technologies Used

- HTML5
- CSS3
- JavaScript
- Google Apps Script
- Google Sheets
- GitHub Pages

---

## 📂 Project Structure

EduExam-Pro/
│
├── index.html
├── instructions.html
├── exam.html
├── review.html
├── admin.html
│
├── css/
│   └── style.css
│
├── js/
│   └── script.js
│
└── README.md

---

## ⚙ Backend Setup (Google Apps Script)

1. Create a Google Sheet containing:
   - Users
   - Questions
   - Responses
   - Results

2. Open:
   Extensions → Apps Script

3. Deploy as **Web App**

4. Replace the script URL in JavaScript:

const SCRIPT_URL = "YOUR_GOOGLE_SCRIPT_URL";

---

## 🌐 Deployment

1. Upload the project to GitHub
2. Go to Repository Settings
3. Open GitHub Pages
4. Select branch **main**
5. Deploy the website

Example:
https://username.github.io/edu-exam-pro

---

## 🏫 Developed For

Department of Electronics & Communication Engineering  
Kamaraj College of Engineering & Technology

---

## 👨‍💻 Author

Alwyn Rajiv

Electronics & Communication Engineering  
FPGA | Embedded Systems | AI Applications

---

## 📜 License

This project is intended for educational and academic use.
