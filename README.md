# 🚗 Vehicle Insurance Fraud Detection

## 📌 Overview

This project predicts whether an insurance claim is fraudulent using machine learning.

## 📊 Dataset

* 15,420 records
* Only 6% fraud cases (highly imbalanced)

## ⚙️ Techniques Used

* Data Preprocessing using ColumnTransformer
* OneHotEncoding for categorical features
* SMOTE for handling imbalance
* Random Forest & XGBoost models
* Hyperparameter tuning (GridSearchCV)

## 📈 Evaluation Metrics

* Precision, Recall, F1-score
* ROC-AUC
* Precision-Recall Curve

## 🚀 Model Deployment

* Pipeline built using sklearn
* Accepts raw input data for prediction

## ▶️ How to Run

```bash
python src/predict.py
```

## 🧠 Key Insight

Recall is prioritized to minimize missed fraud cases.

## 📌 Author

Perumall rishi P
