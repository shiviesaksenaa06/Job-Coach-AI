# JobCoach AI 🚀

Imagine having a personal career coach at your fingertips — one that instantly analyzes your resume, crafts a tailored cover letter, guides your career growth, and even helps you find live job openings.  

Over four days at the **Applied Gen AI Hackathon**, our team (Batta Aditya Yadav, Kiran Rajkumar Kannan, and Shivie Saksenaa) built **JobCoach AI** — an AI-powered career assistant that wraps everything from resume upload to job applications into one seamless workflow.

---

## ✨ Features

### 📄 Resume–Job Description Matching
- Upload your PDF resume and paste any job description.  
- Google Gemini (via LangChain) extracts skills, calculates a **compatibility score (30–95%)**, and generates a report with **strengths, gaps, and actionable tips**.

### 📝 One-Click Cover Letter Generator
- Enter your name, company, hiring manager, and tone (Professional, Enthusiastic, Confident, or Creative).  
- Instantly generates a **keyword-rich cover letter** you can download as `.txt`, copy, or regenerate.

### 💬 24/7 Career Chat
- Ask questions like *“How can I improve this resume?”* or *“Which skills should I learn next?”*  
- Powered by a custom **LLMChain prompt** that ensures context-aware mentoring from Google Gemini.

### 🔎 Built-in Job Search
- Powered by **RapidAPI’s jSearch endpoint**.  
- Get live job postings (title, company, location, remote flag, date).  
- Each listing appears in a neat **Streamlit expander with an “Apply” button** — no extra tabs needed.

---

## ⚙️ Tech Stack
- **Google Gemini 1.5 Flash** (via LangChain)
- **Streamlit** (frontend & workflow integration)
- **RapidAPI jSearch** (live job listings)
- **spaCy** (fallback for skills extraction)
- **PyPDF2** (resume parsing)
- **ngrok** (for demo deployment)

---

## 🚀 Getting Started

### 1. Clone the repo
```bash
git clone https://github.com/your-username/jobcoach-ai.git
cd jobcoach-ai
pip install -r requirements.txt
```
pip install -r requirements.txt
### 2. Create .env file 
GOOGLE_API_KEY=your_google_key
RAPIDAPI_KEY=your_rapidapi_key

### 3. Run the app 
streamlit run app.py
