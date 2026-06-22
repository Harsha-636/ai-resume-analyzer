# 🎯 AI Resume Analyzer — Powered by Google Gemini

> Upload your resume and get instant AI-powered analysis — ATS score, skills gap, job role match, bullet point rewrites, and a personalized improvement roadmap.

[![Python](https://img.shields.io/badge/Python-3.11+-blue.svg)](https://python.org)
[![Flask](https://img.shields.io/badge/Flask-3.0-green.svg)](https://flask.palletsprojects.com)
[![Gemini](https://img.shields.io/badge/Google-Gemini%20AI-orange.svg)](https://ai.google.dev)

---

## ✨ AI Features

| Feature | Description |
|---------|-------------|
| 📊 **Resume Score** | Overall score out of 100 with section breakdown |
| 🤖 **ATS Score** | Applicant Tracking System compatibility score |
| ✅ **Skills Analysis** | Found skills vs missing skills for target role |
| 💼 **Job Role Fit** | Match % for 3 relevant job roles with reasoning |
| ✏️ **Bullet Rewrites** | AI rewrites weak bullets with metrics and impact |
| 🗺️ **Improvement Roadmap** | Prioritized action plan (High/Medium/Low) |
| 🔍 **Keyword Analysis** | ATS keywords present and missing |
| 🎤 **Interview Tips** | Personalized tips based on your resume |

---

## 🛠️ Tech Stack

- **Backend:** Python, Flask, REST API
- **AI:** Google Gemini 1.5 Flash API
- **PDF Parsing:** PyPDF2
- **Frontend:** Vanilla JS, HTML5, CSS3 (dark UI)
- **Deploy:** Render, Gunicorn

---

## 🚀 Quick Start

```bash
git clone https://github.com/Harsha-636/ai-resume-analyzer.git
cd ai-resume-analyzer
pip install -r requirements.txt
export GEMINI_API_KEY=your_key_here
python app.py
```

Get free Gemini API key: https://aistudio.google.com/app/apikey

---

## ☁️ Deploy on Render

1. Push to GitHub
2. Connect repo on render.com
3. Add env variable: `GEMINI_API_KEY=your_key`
4. Build: `pip install -r requirements.txt`
5. Start: `gunicorn app:app --bind 0.0.0.0:$PORT`

---

## 👨‍💻 Author

**Sai Harsha Vardhan Reddy Avula** — B.Tech CSE @ KMCE Hyderabad (2027)

[![LinkedIn](https://img.shields.io/badge/LinkedIn-Connect-blue)](https://linkedin.com/in/harsha-avula)
[![GitHub](https://img.shields.io/badge/GitHub-Follow-black)](https://github.com/Harsha-636)
