# 📄 Resume ZIP Analyzer using LangChain & LLMs

## 🔍 Project Overview
HR teams receive resumes in bulk as ZIP files.  
Manually extracting candidate details is time-consuming and inconsistent.

This project automates resume understanding using LLMs and LangChain.

## 🚀 Features
- Upload ZIP file containing multiple resumes
- Supports PDF and DOCX
- LLM-based resume understanding
- Structured output using TypedDict schema
- CSV export for HR analysis
- Streamlit UI

## 🧠 Tech Stack
- Python
- Streamlit
- LangChain
- Google Gemini LLM
- PyPDF2, python-docx

## ⚙️ How It Works
1. Upload ZIP file
2. Extract resume text
3. Convert unstructured text → structured schema
4. Aggregate results
5. Download CSV

## ▶️ How to Run

https://github.com/user-attachments/assets/1b95e7c6-50bf-41c0-9991-0f6556e1284f


```bash
pip install -r requirements.txt
streamlit run app.py
