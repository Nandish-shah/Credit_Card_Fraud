
## 📌 Project Overview

This project aims to detect **fraudulent credit card transactions** using advanced machine learning techniques. Fraudulent activity detection is a critical challenge in financial institutions due to the large volume of transactions and the rarity of fraud cases. This project addresses this by focusing on **imbalanced data handling** and **robust classification models**.

---

## 🎯 Aim

To accurately identify fraudulent credit card transactions using machine learning, with a strong focus on **imbalanced datasets** and **performance evaluation**.

---

## 🧠 What I Learned

- Working with real-world, **imbalanced financial datasets**
- Data preprocessing techniques for fraud analysis
- Advanced classification algorithms like **Random Forest**, **XGBoost**, etc.
- Oversampling techniques such as **SMOTE** (Synthetic Minority Oversampling)
- Model evaluation using **Precision**, **Recall**, **F1-Score**, and **ROC-AUC**
- Feature engineering and selection

---

## 🛠 Technologies Used

- **Python**
- **Pandas** – Data manipulation
- **Scikit-learn** – Model building and evaluation
- **Imbalanced-learn** – SMOTE and resampling
- **Matplotlib / Seaborn** – Data visualization (optional)

---

## 📂 Dataset

- **Source:** [Kaggle - Credit Card Fraud Detection](https://www.kaggle.com/datasets/mlg-ulb/creditcardfraud)
- **Details:**
  - 284,807 transactions
  - Only 492 are fraudulent (~0.17%)
  - Features are anonymized (V1 to V28), along with `Amount`, `Time`, and `Class`

---

## 🧪 Project Workflow

1. **Data Loading**
2. **Exploratory Data Analysis (EDA)**
3. **Preprocessing**
   - Feature scaling
   - Data balancing using SMOTE
4. **Model Training**
   - Random Forest, Logistic Regression, XGBoost
5. **Model Evaluation**
   - Confusion Matrix
   - ROC-AUC Curve
   - Classification Report

---

## 📈 Results

- Achieved high **recall** and **F1-score** for the minority (fraud) class
- Demonstrated the effectiveness of **SMOTE** in balancing the dataset
- **ROC-AUC Score:** > 0.95 with tuned models

---

## ✅ Conclusion

This project provided hands-on experience with detecting financial fraud using machine learning. It emphasized the importance of **handling data imbalance**, **selecting the right evaluation metrics**, and **building reliable models** that can be used in real-world fintech systems.
