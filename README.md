# Open World Fraud Behavior Detection in Banking

## Overview
This project focuses on detecting both known fraud transactions and unknown suspicious behaviors in banking systems using machine learning techniques.

The project uses anomaly detection, deep learning, and classification models to improve fraud detection performance.

---

## Models Used

### Version 1
- Isolation Forest
- Random Forest

### Final Version
- Autoencoder
- Isolation Forest
- XGBoost

---

## Working Pipeline

### Stage 1 — Autoencoder
Detects unusual transaction behavior using reconstruction error.

### Stage 2 — Isolation Forest
Detects anomalous and unknown transaction patterns.

### Stage 3 — XGBoost
Classifies known fraud and normal transactions.

---

## Open-World Metrics
- KCA — Known Classification Accuracy
- URA — Unknown Rejection Accuracy
- OWRA — Open-World Recognition Accuracy
- FAR — False Acceptance Rate

---

## Dataset
This project uses the Credit Card Fraud Detection dataset from Kaggle.

Dataset Link:  
https://www.kaggle.com/datasets/mlg-ulb/creditcardfraud

---

## Technologies Used
- Python
- Pandas
- NumPy
- Scikit-learn
- TensorFlow / Keras
- XGBoost
- Matplotlib
- Seaborn

---

## Repository Structure

```text
open-world-fraud-detection/
│
├── README.md
│
├── notebooks/
│   ├── Autoencoder_IF_XGBoost.ipynb
│   └── IsolationForest_RandomForest.ipynb
```

---

## Features
- Open-world fraud detection
- Unknown fraud rejection
- Multi-stage fraud detection pipeline
- Machine learning and deep learning models
- Custom fraud detection metrics

---

## Objective
To build a banking fraud detection system that can detect both known fraud transactions and previously unseen suspicious behaviors.

---

## Team Project
This project was developed collaboratively as part of a Minor Project.
