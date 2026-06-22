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
