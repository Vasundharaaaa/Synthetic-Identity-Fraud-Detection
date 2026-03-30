# 🚨 Synthetic Identity Fraud Detection System
### 🧠 Anomaly-Based Machine Learning System for Detecting Synthetic Financial Identities

---

## 📌 Overview
Synthetic identity fraud is one of the fastest-growing financial crimes, where attackers combine real and fabricated information to create seemingly legitimate identities.

This project presents an intelligent system that not only **detects fraudulent transactions** but also **simulates synthetic identity attacks**, making the detection mechanism more robust and realistic.

---

## 🎯 Problem Statement
Traditional fraud detection systems rely only on historical fraud data, which limits their ability to detect new or unseen fraud patterns.

👉 This project addresses that gap by:
- Generating synthetic fraudulent identities
- Training an anomaly detection model on both real and simulated data
- Assigning a dynamic fraud risk score

---

## 💡 Key Features

✨ **Synthetic Identity Generation**
- Artificially creates fraud-like data patterns
- Simulates real-world attack scenarios

🤖 **Anomaly Detection Model**
- Uses Isolation Forest for unsupervised fraud detection
- Identifies outliers in high-dimensional data

📊 **Advanced Visualizations**
- Class imbalance analysis
- Confusion matrix heatmap
- Anomaly scatter plots
- Risk score distribution

📈 **Fraud Risk Scoring System**
- Assigns each transaction a score (0–100%)
- Helps interpret model decisions

🧠 **Feature Importance Analysis**
- Highlights which variables influence fraud detection most

---

## 🧠 Machine Learning Approach

### 🔹 Model Used:
- **Isolation Forest**
  - An unsupervised anomaly detection algorithm
  - Efficient in detecting rare fraud patterns

### 🔹 Why Isolation Forest?
- Works well with imbalanced datasets
- Does not require labeled fraud data
- Scales efficiently for large datasets

---

## 📊 Dataset

- **Credit Card Fraud Detection Dataset (Kaggle)**
- Contains anonymized features (V1–V28), Amount, Time, and Class

### 📌 Key Insight:
- Highly imbalanced dataset:
  - ~99.8% Normal
  - ~0.2% Fraud

---

## 📈 Results & Performance

| Metric        | Value |
|--------------|------|
| Accuracy      | ~90% |
| Recall (Fraud)| Improved with synthetic data |
| Precision     | Lower (expected in anomaly detection) |

📌 The model effectively identifies anomalous transactions while maintaining interpretability.

---

## 📊 Visual Outputs

- 📉 Fraud vs Normal Distribution  
- 📊 Confusion Matrix  
- 🔍 Anomaly Detection Plot  
- 📈 Feature Importance Graph  
- 📊 Risk Score Histogram  

---

## 🚀 How to Run

```bash
1. Upload dataset (creditcard.csv)
2. Run the notebook in Google Colab
3. Execute all cells sequentially
```

## 🔁 System Pipeline

Raw Data → Preprocessing → Synthetic Data Injection → Model Training → Prediction → Risk Scoring → Visualization

🔮 Future Enhancements
🎤 Voice-based input system for fraud prediction
🌐 Web application (Streamlit dashboard)
🧠 Explainable AI using SHAP/LIME
⚡ Real-time fraud detection pipeline

“This system does not just detect fraud — it anticipates how fraud is created.”

⭐ If you found this project interesting, consider giving it a star!

👩‍💻 Author-Vasuntthara Dhayalan
