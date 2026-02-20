# <img width="50" height="45" alt="image" src="https://github.com/user-attachments/assets/df674aa8-359a-44c7-86ea-b8b654ad9573" /> SmartHire AI 
                                                  
SmartHire AI is an AI-powered Applicant Tracking System (ATS) designed to transform the hiring experience.Built with tools like Streamlit and advanced AI 
integration, it intelligently scans resumes, compares them with job descriptions, and delivers precise hiring insights. From calculating match percentages to 
identifying keyword gaps, SmartHire AI turns complex resume analysis into clear, actionable feedback.

________________________________________
## 🔍Overview

SmartHire AI bridges the gap between talent and oppourtunity. It empowers job seekers and recruiters by evaluating how effectively a resume aligns with a specific
role. By stimulating a real world ATS environment, the platform generates sturctured, professional feedback highlighting:

📊 ATS Percentage Match Score

✅ Strengths aligned with job requirements

❌ Weaknesses & skill gaps

🔑 Missing Keywords

💡 Final hiring recommendation
________________________________________
## 📌 Problem Statement
Rectuiters receive hunderds or even thousands of resumes for a single job posting. manually screening them is time consuming, biased, and inefficient. Companies
often lose top talent because of slow or inaccurate filtering.

## Solution
To solve this problem, we built SmartHire AI, an AI-powered Applicant Tracking System that analyzes resumes against job descriptions and provides intellegent
matching and insights.
_________________________________________
##  <img width="26" height="25" alt="image" src="https://github.com/user-attachments/assets/82da48f6-cafe-4b54-955c-6d294bf6286f" /> Tech stack

•	Python

•	Streamlit – Web interface

•	Google Gemini 2.5 Flash – AI resume analysis

•	pdf2image – Convert PDF resume to image

•	Pillow (PIL) – Image processing

•	python-dotenv – Secure API key management
________________________________________
## ⚙️Features:

<img width="1356" height="633" alt="image" src="https://github.com/user-attachments/assets/ad687f41-16c1-43ba-abe5-ad268d849085" />

•	Upload Resume in PDF format

•	Enter Job Description

•	Get HR-style evaluation

•	Get ATS match percentage

•	Clean and interactive UI

•	Secure environment variable handling
________________________________________
## 📂Project Structure:

```python
SmartHire-AI/
│
├── ATS_project.py
├── requirements.txt
├── .env               # Not pushed to GitHub
├── .gitignore
└── README.md
```
________________________________________
## <img width="26" height="25" alt="image" src="https://github.com/user-attachments/assets/b0e490f7-2a4c-4a2d-bd19-10b9d58a0db1" /> Environment Setup:

1️. Clone the Repository;

bash:

```python
git clone https://github.com/your-username/SmartHire-AI.git

cd SmartHire-AI
```
________________________________________
2️. Install Dependencies;
```python
pip install -r requirements.txt
```
If requirements file is not available;

```python
pip install streamlit google-generativeai pdf2image pillow python-dotenv
```
_________________________
3️. Setup Google API Key

👉Generate your API key 

Create a .env file in the root directory;

```python
GOOGLE_API_KEY=your_actual_api_key_here
```
⚠ Important:

•	Do NOT upload .env to GitHub

•	Add .env to .gitignore
________________________________________
 Running the Application;
```python
streamlit run ATS_project.py
```
The application will open automatically in your browser.
________________________________________
## 🧠How It Works:




1.	User uploads a resume (PDF)
2.	PDF is converted into image format
3.	Resume image + Job Description is sent to Gemini API
4.	AI evaluates:

    o	Skill alignment

    o	Role compatibility

    o	Keyword gaps

    o	Overall match percentage

6.	Structured feedback is displayed on the UI
________________________________________
## 🔒Security Best Practices:

•	API keys stored securely using environment variables

•	.env file excluded via .gitignore

•	No hardcoded credentials in source code
________________________________________
## <img width="26" height="25" alt="image" src="https://github.com/user-attachments/assets/507f71c7-f4b4-4564-aca0-95f7e52b7a1e" /> Future Enhancements

•	Multi-page resume support

•	Downloadable ATS report (PDF)

•	Skill visualization charts

•	Resume improvement suggestions section

•	Deployment on Streamlit Cloud
________________________________________
## <img width="26" height="25" alt="image" src="https://github.com/user-attachments/assets/750b8bcf-ebbd-4c9e-9996-402ddb4e5db0" /> Use Cases

•	Students preparing for campus placements

•	Job seekers optimizing resumes

•	HR professionals screening candidates

•	AI integration learning projects
________________________________________
## 👩‍💻Meet the minds behind SmartHire AI

SmartHire AI is proudly developed by two passionate engineering students,

Kritika Jain 

B.Tech – Artificial Intellengence & Data Science

Mudra Chauhan

B.Tech - Computer Science Engineering

Project: SmartHire AI – ATS Resume Analyzer
________________________________________

