# Phishing Website Analysis 🚨

A data science project to analyze phishing website characteristics and build a machine-learning based phishing risk detector.

---

## 🔎 Project Overview

Many phishing attacks exploit URL and webpage characteristics to trick users (e.g. long URLs, suspicious anchors, SSL issues, sub-domains).  
This project leverages a public dataset of ~11,000 websites (phishing and legitimate) and performs:

- Exploratory Data Analysis (EDA) to uncover distinguishing patterns  
- Statistical hypothesis testing (t-test, chi-square) to validate significant risk-indicating features  
- A classification pipeline using Logistic Regression (with class balancing) to predict phishing risk  
- Comparison with a Random Forest model to evaluate performance vs interpretability  
- A simple phishing **risk scoring scheme** (Low / Medium / High) based on model probability — suitable for real-world use

---

## 📁 Repository Structure

- `phishing_website_analysis.ipynb` — Main Jupyter/Colab notebook (data loading, EDA, stats tests, modeling, evaluation, risk scoring)  
- `requirements.txt` — Python dependencies required to run the notebook  
- `README.md` — Project documentation  

---

## 🚀 How to Run

1. Download / clone this repository  
2. Install dependencies:  
   ```bash
   pip install -r requirements.txt
