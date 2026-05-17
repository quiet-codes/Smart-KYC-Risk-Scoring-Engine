<div align="center">

# Smart KYC Risk Scoring Engine

### AI-Powered AML Risk Classification & Explainable Customer Onboarding

An intelligent KYC compliance system that detects AML/fraud risk signals, classifies customers into risk categories, and generates explainable onboarding recommendations.

Built for hackathon innovation in **FinTech + AI + Compliance**.

![Python](https://img.shields.io/badge/Python-3.x-blue)
![Scikit-Learn](https://img.shields.io/badge/ML-ScikitLearn-orange)
![Status](https://img.shields.io/badge/Status-Completed-green)
![License](https://img.shields.io/badge/License-MIT-red)

</div>

---

# Problem Statement

Traditional KYC verification systems are often:

- Manual and time-consuming
- Hard to scale
- Inconsistent across analysts
- Lack explainability
- Slow in fraud detection

This project solves that using **Machine Learning + Explainable AI** to automate customer risk scoring.

---

# Key Features

✅ AML risk signal detection  
✅ Fraud pattern recognition  
✅ Automated risk classification  
✅ Explainable AI reasoning  
✅ Intelligent onboarding recommendations  
✅ Compliance-driven decision making  

---

# System Architecture

<p align="center">
  <img src="assets/architecture.png" width="1000">
</p>

The pipeline follows:

```text
Customer Data
    ↓
Data Preprocessing
    ↓
Feature Engineering
    ↓
Risk Signal Extraction
    ↓
ML Risk Scoring Engine
    ↓
Explainability Layer
    ↓
Decision Recommendation
```

---

# Tech Stack

## Programming Language

- Python

## Libraries

- Pandas
- NumPy
- Scikit-learn
- Matplotlib
- Seaborn
- XGBoost
- SHAP

## Development Tools

- Jupyter Notebook
- Git
- GitHub

---

# Risk Features Used

The engine analyzes:

| Feature | Description |
|---------|-------------|
| Age | Customer age |
| Occupation Risk | Profession risk level |
| Country Risk | Geography-based compliance score |
| Transaction Volume | Financial activity |
| PEP Status | Politically exposed person |
| Source of Funds | Income legitimacy |
| Sanctions Exposure | Compliance violations |
| Behavioral Signals | Fraud indicators |

---

# Machine Learning Pipeline

## 1. Data Preprocessing

- Missing value handling
- Label encoding
- Feature normalization
- Outlier treatment

## 2. Feature Engineering

- AML signals
- Fraud indicators
- Derived compliance metrics

## 3. Model Training

Models explored:

- Logistic Regression
- Random Forest
- Gradient Boosting
- XGBoost

## 4. Evaluation

Metrics:

- Accuracy
- Precision
- Recall
- F1 Score

---

# Model Performance

<p align="center">
  <img src="assets/confusion_matrix.png" width="750">
</p>

The confusion matrix demonstrates strong classification across:

- Low Risk
- Medium Risk
- High Risk

---

# Feature Importance Analysis

<p align="center">
  <img src="assets/feature_importance.png" width="850">
</p>

Key drivers influencing risk decisions:

- Transaction Volume
- Country Risk
- PEP Status
- Source of Funds
- Occupation Risk

---

# Explainable AI Output

Instead of only predicting a score, the engine explains *why*.

Example:

```json
{
  "customer_id": 103,
  "risk_score": 91,
  "risk_level": "High",
  "reasons": [
    "PEP detected",
    "High-risk jurisdiction",
    "Abnormal transaction activity"
  ],
  "recommendation": "Enhanced Due Diligence"
}
```

---

# Sample Predictions

| Customer ID | Risk Score | Risk Level | Recommendation |
|------------|------------|------------|----------------|
| 101 | 18 | Low | Approve |
| 102 | 62 | Medium | Manual Review |
| 103 | 91 | High | Enhanced Due Diligence |

---

# Project Structure

```bash
Smart-KYC-Risk-Scoring-Engine/
│
├── assets/
│   ├── architecture.png
│   ├── confusion_matrix.png
│   ├── feature_importance.png
│
├── data/
├── notebooks/
├── models/
├── src/
├── outputs/
├── requirements.txt
└── README.md
```

---

# Installation

Clone repository:

```bash
git clone https://github.com/quiet-codes/Smart-KYC-Risk-Scoring-Engine.git
```

Move into directory:

```bash
cd Smart-KYC-Risk-Scoring-Engine
```

Install dependencies:

```bash
pip install -r requirements.txt
```

---

# Usage

Launch notebook:

```bash
jupyter notebook
```

or run:

```bash
python main.py
```

---

# Business Impact

This system helps financial institutions:

- Reduce fraud exposure
- Improve regulatory compliance
- Speed up onboarding
- Reduce manual verification cost
- Improve explainability

---

# Future Improvements

- Real-time API deployment
- Streamlit dashboard
- Live sanction list integration
- Graph-based fraud detection
- Deep learning anomaly detection

---

# Team

Built during Hackathon by:

## Ashish Kumar

GitHub:

https://github.com/quiet-codes

---

# Acknowledgements

Special thanks to the hackathon organizers for the problem statement and challenge.

---

# License

MIT License
