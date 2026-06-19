# 🛡️ Hunting Digital Frauds with Classification Algorithms (AI/ML Project)

![Python](https://img.shields.io/badge/python-3670A0?style=for-the-badge&logo=python&logoColor=ffdd54)
![Pandas](https://img.shields.io/badge/pandas-150458?style=for-the-badge&logo=pandas&logoColor=white)
![NumPy](https://img.shields.io/badge/numpy-013243?style=for-the-badge&logo=numpy&logoColor=white)
![Scikit-Learn](https://img.shields.io/badge/scikit--learn-F7931E?style=for-the-badge&logo=scikit-learn&logoColor=white)
![Matplotlib](https://img.shields.io/badge/matplotlib-ffffff?style=for-the-badge&logo=matplotlib&logoColor=black)

---

# 📍 Problem Statement: The Digital Fraud Challenge

In today’s digital India, millions of online transactions happen every second.  
While most are legitimate, a small percentage are **fraudulent transactions**.

👉 The problem is that fraud cases are **rare**, making it difficult for machines to detect them.  
👉 This creates a “needle in a haystack” problem for AI systems.

---

# 💡 Solution: AI-Based Fraud Detection System

This project builds an intelligent machine learning system that:
- Detects fraudulent transactions
- Learns patterns from historical data
- Improves detection using balanced datasets
- Provides interpretable decision-making using a Decision Tree model

---

# ⚙️ How the System Works (Step-by-Step)

## 1️⃣ Data Cleaning Engine
Real-world data is messy, so the system:
- Removes duplicates
- Handles missing values
- Fixes infinite values
- Converts incorrect formats

✔ Ensures model stability in real-world scenarios

---

## 2️⃣ Feature Engineering
- Extracts **hour from transaction time**
- Encodes categorical variables (Label Encoding)
- Removes unnecessary columns like transaction IDs

✔ Improves model learning capability

---

## 3️⃣ Handling Imbalanced Data (SMOTE)
Fraud cases are rare, so:
- SMOTE generates synthetic fraud samples
- Balances dataset (Fraud = Non-Fraud)

✔ Prevents model bias toward “non-fraud” class

---

## 4️⃣ Machine Learning Model
We use:
👉 Decision Tree Classifier

Why?
- Easy to interpret
- Works well on structured data
- Provides explainable fraud detection rules

---

# 📊 Model Performance

| Metric | Value |
|--------|------|
| Accuracy | ~52% |
| Precision (Fraud) | 0.32 |
| Recall (Fraud) | 0.48 |
| F1 Score (Fraud) | 0.38 |

---

## 📌 Confusion Matrix
