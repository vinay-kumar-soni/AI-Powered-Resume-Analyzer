# 🤖 AI Powered Resume Analyzer

An AI-powered web application that analyzes resumes and provides ATS-style feedback using Google's Gemini AI. Users can upload resumes, compare them with job descriptions, and receive detailed insights, strengths, improvement suggestions, and match scores.

## 🚀 Features

* User Registration & Login System
* Secure Authentication
* Resume Upload (PDF & DOCX)
* AI-Powered Resume Analysis using Gemini API
* ATS Match Score Calculation
* Strengths & Improvement Suggestions
* Resume History Tracking
* Interactive Analytics Dashboard
* Skill Match Visualization
* Responsive Web Interface

## 🛠️ Tech Stack

### Backend

* Python
* Flask
* SQLAlchemy
* Flask-Login
* SQLite

### Frontend

* HTML5
* CSS3
* Jinja2 Templates

### AI Integration

* Google Gemini API

### Data Visualization

* Plotly

## 📂 Project Structure

```text
resume-analyzer/
│
├── app.py
├── requirements.txt
├── .gitignore
├── static/
│   └── css/
├── templates/
│   ├── index.html
│   ├── login.html
│   ├── register.html
│   ├── dashboard.html
│   ├── upload.html
│   ├── result.html
│   ├── history.html
│   └── analytics.html
└── .env
```

## ⚙️ Installation

### 1. Clone Repository

```bash
git clone https://github.com/vinay-kumar-soni/AI-Powered-Resume-Analyzer.git
cd AI-Powered-Resume-Analyzer
```

### 2. Create Virtual Environment

```bash
python -m venv venv
```

### 3. Activate Virtual Environment

Windows:

```bash
venv\Scripts\activate
```

### 4. Install Dependencies

```bash
pip install -r requirements.txt
```

### 5. Create .env File

```env
GEMINI_API_KEY=your_gemini_api_key
SECRET_KEY=your_secret_key
```

### 6. Run Application

```bash
python app.py
```

Open:

```text
http://127.0.0.1:5000
```

## 📊 Key Functionalities

* Upload resumes in PDF or DOCX format.
* Analyze resumes against job descriptions.
* Generate ATS compatibility scores.
* Identify strengths and improvement areas.
* Track previous resume analyses.
* View analytics and performance trends.

## 🔒 Security

* API keys are stored using environment variables.
* Sensitive information is excluded from version control using `.gitignore`.
* Passwords are securely hashed before storage.

## 📸 Screenshots

### 1️⃣ Registration Page
<img width="1366" height="673" alt="Register" src="https://github.com/user-attachments/assets/7ba74de0-496a-4064-89cc-5efad73332eb" />

### 2️⃣ Dashboard
<img width="1366" height="677" alt="Dashboard" src="https://github.com/user-attachments/assets/0c60fdf2-9bd6-436b-9be9-1da555b35d28" />

### 3️⃣ Resume Upload Page
<img width="1366" height="684" alt="Upload" src="https://github.com/user-attachments/assets/4ed17427-cd68-40e2-b9c4-915f254b87f9" />

### 4️⃣ Resume Analysis - Part 1
<img width="1366" height="683" alt="Analysis_1" src="https://github.com/user-attachments/assets/bd151321-8bc6-4621-8648-19e00ef05dc6" />

### 5️⃣ Resume Analysis - Part 2
<img width="1366" height="673" alt="Analysis_2" src="https://github.com/user-attachments/assets/6d9ddd6c-b2a7-4e66-8273-2b9318df4465" />

### 6️⃣ Data Visualization Dashboard - Part 1
<img width="1366" height="671" alt="Data Visualization_1" src="https://github.com/user-attachments/assets/565a8dd7-3327-4f86-81ad-923d797d844c" />

### 7️⃣ Data Visualization Dashboard - Part 2
<img width="1366" height="674" alt="Data Visualization_2" src="https://github.com/user-attachments/assets/9ae09fc6-a1ad-4058-a202-093b9a13cd97" />

### 8️⃣ Resume History
<img width="1366" height="676" alt="History" src="https://github.com/user-attachments/assets/5311b29f-f75c-40fd-9894-df9da9310bd7" />

## 🎯 Future Improvements

* Multi-language resume analysis
* Resume ranking system
* Job recommendation engine
* Export analysis reports as PDF
* Advanced ATS optimization suggestions

## 👨‍💻 Author

**Vinay Kumar Soni**

* B.Tech Computer Science Engineering (2026)

## ⭐ Support

If you found this project useful, consider giving it a star on GitHub.
