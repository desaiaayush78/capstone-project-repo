# 🧠 Capstone Project: End-to-End Fraud Detection System

This repository contains a full-stack, real-world fraud detection solution built as part of a data science capstone project. It combines machine learning, web scraping, and model deployment workflows across three modular components.

---

## 🔍 Modules

### 1. 📊 Capstone_Fraud_Detection Module
- Trains a hybrid fraud detection model using XGBoost and rule-based risk scoring.
- Applies extensive feature engineering, anomaly detection, and probability-based scoring.
- Outputs: fraud predictions, confidence scores, and risk classifications.

### 2. 🌐 Capstone_WebScrapping_ Module
- Uses NewsAPI + NLP (spaCy) to scrape and analyze adverse media mentions.
- Automatically scores individuals based on appearance in financial crime-related news.
- Outputs: article summaries, PDF reports, and person-level risk scores.

### 3. 🚀 Capstone_Deployment_ Module
- Loads the trained model and predicts on new unseen transactions.
- Ensures consistent preprocessing and generates outputs for business consumption.
- Includes fraud risk visualizations and probability distribution charts.

---

## 🧰 Tech Stack

- Python (Pandas, NumPy, Scikit-learn, XGBoost, spaCy)
- Flask / Streamlit for dashboard deployment
- Jupyter Notebooks for development
- Git & GitHub for version control
- NewsAPI, Newspaper3k for scraping
- Visualizations: Matplotlib, Seaborn, PDF generation

---

## 📦 Dataset Info

- Primary dataset: IEEE-CIS Fraud Detection (Kaggle)
- External sources: news articles related to financial crimes (via NewsAPI)

---

## 📁 Folder Structure

```
capstone-project-repo/
│
├── Capstone_Fraud_Detection Module/
├── Capstone_WebScrapping_ Module/
├── Capstone_Deployment_ Module/
├── Literature_Review_aayush desai.docx
└── README.md
```

---

## 🧑‍💻 Author

**Aayush Desai**  
Graduate Student, M.S. Data Science @ Pace University  
LinkedIn: [aayush-desai-ad041799](https://www.linkedin.com/in/aayush-desai-ad041799)

Email: desaiaayush78.ad@gmail.com

PaceEmail-ad93569n@pace.edu

---
