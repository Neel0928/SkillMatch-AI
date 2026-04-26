# SkillMatch-AI
An AI-powered job portal that matches resumes with job descriptions using machine learning (TF-IDF &amp; cosine similarity). Built using Node.js, PostgreSQL, and Python



An AI-powered Job Portal that intelligently matches candidate resumes with job descriptions using Machine Learning (TF-IDF & Cosine Similarity). Built as a full-stack application without using any external APIs.

---

## 📌 Overview

HireSense AI is a smart job portal designed to improve the hiring process by analyzing resumes and comparing them with job descriptions. Instead of simple keyword matching, it uses **text similarity algorithms** to generate a **match score (%)**, helping candidates and recruiters make better decisions.

---

## 🎯 Features

### 👤 Candidate
- Register & Login
- Upload Resume (PDF / TXT)
- View Job Listings
- View Match Score for each job
- Apply to Jobs

### 🧑‍💼 Recruiter
- Register & Login
- Post Job Listings
- View Applicants
- See Candidates Ranked by Match Score

### 🧠 AI Matching System
- Extracts text from resume
- Converts text using TF-IDF (scikit-learn)
- Computes similarity using cosine similarity
- Generates Match Score (%)

---

## 🛠️ Tech Stack

### Frontend
- HTML
- CSS
- Bootstrap
- JavaScript

### Backend
- Node.js
- Express.js

### Database
- PostgreSQL

### AI / Machine Learning
- Python
- NumPy
- Pandas
- scikit-learn


