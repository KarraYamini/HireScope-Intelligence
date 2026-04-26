# 🚀 HireScope Intelligence

## AI-Based Resume Screening, Job Role Prediction & Job Recommendation System using NLP and Machine Learning

---

## 📌 Overview

HireScope Intelligence is an AI-powered recruitment intelligence web application built using **Streamlit, Machine Learning, and NLP**. It automates resume screening, predicts suitable job roles, analyzes skill gaps, and recommends relevant job opportunities based on similarity matching between resumes and job descriptions.

The system is designed to help:

- 👨‍💼 Recruiters reduce manual resume screening effort
- 👩‍🎓 Job seekers identify suitable career paths

---

## ✨ Key Features

- 📄 Upload or paste resume (PDF or text)
- 🧠 Predict job role using ML model
- 🔍 Extract and analyze skills from resume
- ❌ Identify missing skills for target role
- 📊 Skill match analysis with visualization
- 📘 Learning path recommendations
- 🏢 Top MNC job links for each role
- 🔎 Job recommendation using cosine similarity
- 📈 Resume vs Job Description match score
- 🔐 Login & user history tracking (SQLite)

---

## 🧰 Tech Stack

**Frontend:**

- Streamlit

**Backend / ML:**

- Python
- Scikit-learn
- Logistic Regression
- Cosine Similarity

**NLP:**

- NLTK
- Regex

**Data Handling:**

- Pandas
- NumPy

**Visualization:**

- Plotly

**File Handling:**

- PyPDF2

**Database:**

- SQLite3

---

## 📂 Project Structure

```
HireScope-Intelligence/
│
├── app.py                         # Main Streamlit application
├── model.pkl                     # Trained ML model
├── tfidf.pkl                     # TF-IDF vectorizer
├── label_encoder.pkl             # Encodes job roles
├── job_dataset_final.csv         # Job description dataset
├── users.db                      # SQLite database
├── requirements.txt              # Dependencies
└── README.md                     # Project documentation
```

---

## ⚙️ Installation Guide

### 1️⃣ Clone Repository

```bash
git clone https://github.com/your-username/HireScope-Intelligence.git
cd HireScope-Intelligence
```

### 2️⃣ Create Virtual Environment (Optional)

```bash
python -m venv venv
venv\Scripts\activate   # Windows
```

### 3️⃣ Install Dependencies

```bash
pip install -r requirements.txt
```

### 4️⃣ Run Application

```bash
streamlit run app.py
```

---

## 🧪 How It Works

1. Upload resume (PDF/text)
2. System preprocesses and cleans text
3. TF-IDF converts text into vectors
4. ML model predicts job role
5. Cosine similarity matches resume with job descriptions
6. System recommends top jobs + skill gap analysis

---

## 📊 Example Output

- 🎯 Predicted Role: Data Scientist
- 🧠 Skills Extracted: python, machine learning, pandas
- ❌ Missing Skills: matplotlib, deep learning
- 📊 Match Score: 82%
- 🏢 Recommended Jobs: Google, Amazon, Microsoft

---

## 📁 Datasets Used

### 1. UpdatedResumeDataset (Kaggle)

- Category (Job Role)
- Resume (Text)

### 2. Advanced\_job\_dataset (Custom)

- Job\_Role
- Description

---

## 🚀 Future Enhancements

- 🔥 Deep Learning-based resume classification
- 🌐 Live job scraping from portals
- 📱 Mobile-friendly UI
- 🤖 Chatbot-based career assistant
- 📊 Advanced analytics dashboard

---

## 👨‍💻 Author

**Karra Yamini**

Github link :[https://github.com/KarraYamini/HireScope-Intelligence]

---

## ⭐ If you like this project

Give a ⭐ on GitHub and share it!

