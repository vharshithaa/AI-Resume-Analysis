# 🧠 AI-Powered Resume Analyzer

The **AI-Powered Resume Analyzer** is a cutting-edge application designed to mimic the expertise of an HR professional. This tool leverages the power of **Google Generative AI (Gemini)** to analyze resumes, evaluate job compatibility, and provide actionable insights for career enhancement.

---

## 📌 Project Overview

The AI-Powered Resume Analyzer acts as your **virtual HR assistant**, offering:

- ✔️ Detailed resume evaluation  
- ✔️ Strength and weakness analysis  
- ✔️ Skill gap identification  
- ✔️ Recommended skill courses  
- ✔️ Job–resume compatibility scoring  
- ✔️ HR-style feedback and improvement insights  

Whether you're a job seeker trying to upgrade your resume or a recruiter looking to evaluate candidates efficiently, this tool simplifies and enhances the resume assessment process.

---

## ✨ Features

### 🔍 General Resume Analysis
- One-line professional resume summary  
- Extracted and categorized skill sets  
- Identification of missing or weak skill areas  
- Actionable suggestions for improvement  
- Personalized course recommendations  
- HR-style strengths and weaknesses breakdown  

### 🎯 Resume–Job Description Matching
- Job-specific resume evaluation  
- Compatibility score (percentage-based)  
- Highlighting of missing skills required for the job  
- Suggestions to improve job readiness  
- Final verdict: *"Resume Ready"* or *"Needs Improvement"*  

---

## 🛠️ Tech Stack

| Component | Technology |
|----------|------------|
| **Frontend** | Streamlit |
| **Backend** | Python |
| **AI Model** | Google Generative AI (Gemini) |
| **PDF Parsing** | pdfplumber |
| **OCR Fallback** | pytesseract |
| **Environment Config** | `.env` for API key security |

---

## ⚙️ How It Works

### 📄 1. Resume Parsing
- Extracts clean text from PDF using **pdfplumber**  
- If text extraction fails (image-based PDF), uses **pytesseract OCR**

### 🤖 2. AI Analysis
- Sends extracted text to **Gemini 2.5 Flash / Pro**  
- Generates detailed feedback:
  - Summary  
  - Skill extraction  
  - Skill gap detection  
  - Recommended improvements  
  - Suggested courses  

### 📊 3. Job Description Matching
- Compares resume skills with job description requirements  
- Provides:
  - Match score  
  - Missing skills  
  - Improvement suggestions  

### 🎓 4. Insightful Feedback
- Offers actionable career-enhancing suggestions  
- Gives a structured, HR-style evaluation  
- Helps the candidate understand strengths and growth areas  

