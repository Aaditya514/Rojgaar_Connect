# Rojgaar Connect

[![MIT License](https://img.shields.io/badge/license-MIT-blue.svg)](LICENSE)  
A Streamlit-based web app that ingests PDF or text job descriptions, surfaces key role insights, flags potential red-flags, suggests salary benchmarks, and provides an AI-driven interview-prep chatbot.

---

## 🚀 Features

- **Job Description Parser**  
  Upload a PDF or plain text Job Description and automatically extract role, required skills and responsibilities.  
- **AI-Driven Insights**  
  Uses Google Gemini API to detect red-flags, recommend salary ranges and highlight missing skills.  
- **Interview Prep Chatbot**  
  Interactive Q&A assistant offering targeted mock-interview questions, company research tips and career guidance.

---

## 🛠 Tech Stack

- **Language & Framework**: Python, Streamlit  
- **AI / NLP**: Google Gemini API  
- **PDF Parsing**: PyPDF2 (or pdfplumber)  
- **Frontend**: Streamlit Components, HTML/CSS  
- **Hosting**: (optional) Streamlit Community Cloud or your choice of cloud provider  

---

## ⚙ Installation

1. Clone the repository
 ``` 
git clone https://github.com/Aaditya514/Rojgaar_Connect.git
cd Rojgaar_Connect
```
3. Create & activate a virtual environment
 ```
python3 -m venv venv
source venv/bin/activate # macOS/Linux
venv\Scripts\activate # Windows
```
5. Install dependencies
```
pip install -r requirements.txt
```
7. Configure your Google Gemini API key  
- Option A: Add directly in `app.py`  
- Option B: Set as an environment variable  
  ```
  export GEMINI_API_KEY="your_api_key_here"    # macOS/Linux
  set GEMINI_API_KEY="your_api_key_here"       # Windows
  ```

---

## ▶️ Usage

streamlit run app.py

- Open your browser at `http://localhost:8501/`  
- Upload a job description (PDF or text)  
- Explore AI-powered insights and chat with the interview-prep assistant

---

