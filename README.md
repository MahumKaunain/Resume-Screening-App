# 🧠 Resume Screening App

A resume screening web app using Python, Streamlit, and scikit-learn. It extracts and cleans text from resumes (DOCX/PDF), applies NLP, and predicts job roles or categories using a trained ML model. Ideal for automating the initial resume filtering process.

---

## 🚀 Features

- Upload `.docx` or `.pdf` resume files
- Clean and preprocess resume text
- Predict job role/category using ML
- Simple, interactive Streamlit UI

---

## 🛠️ Tech Stack

- Python
- Streamlit
- scikit-learn
- docx2txt / pdfminer
- NumPy, pandas, re (regex), joblib

---
app link: http://localhost:8501/

## 🔧 Installation

1. Clone the repository 
git clone https://github.com/your-username/resume-screening-app.git
cd resume-screening-app

2. Install dependencies
pip install -r requirements.txt

3.Run the app                                                                                                                           
streamlit run app.py

4.If streamlit command is not found, use:
python -m streamlit run app.py
