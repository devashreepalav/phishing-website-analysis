# Phishing Website Analysis 🚨

A data science project to analyze phishing website characteristics and build a machine-learning based phishing risk detector.

## 🔎 Project Overview

- Based on a public phishing URL dataset (~11,000 URLs with 30+ URL/webpage features + label: phishing or legitimate).  
- Perform **Exploratory Data Analysis (EDA)** to uncover patterns that differentiate malicious vs legitimate URLs.  
- Use **statistical hypothesis testing** (T-test, Chi-square) to verify which features are significantly associated with phishing.  
- Build and evaluate a **Logistic Regression classifier** (with class balancing) to predict phishing risk.  
- Compare with **Random Forest** to examine performance vs interpretability trade-offs.  
- Provide a **risk-scoring scheme** (Low / Medium / High) based on model probabilities — practical for real-world use.

## 📊 Key Results (sample — update with your final values)

| Metric       | Logistic Regression | Random Forest  |
|--------------|---------------------|----------------|
| Accuracy     | 93 %                | 96 %           |
| Recall       | 92 %                | 97 %           |
| ROC-AUC      | 0.95                | 0.99           |

> **Important insight**: Features such as `URL_of_Anchor`, `Prefix_Suffix`, and `SSLfinal_State` are strong risk indicators — aligns with known phishing heuristics (suspicious anchor links, domain irregularities, certificate issues).

## 🚀 How to Run

1. Clone or download this repository.  
2. Ensure you have Python environment with dependencies:  
   ```bash
   pip install -r requirements.txt


