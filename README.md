# 💳 Credit Card Fraud Detection using Machine Learning

This project builds a machine learning pipeline to detect fraudulent transactions in an imbalanced dataset using a Random Forest Classifier. 

---

## 📁 Dataset

- Source: [Kaggle – Credit Card Fraud Detection](https://www.kaggle.com/datasets/mlg-ulb/creditcardfraud)
- Contains 284,807 transactions with 31 features including anonymized variables (`V1` to `V28`), `Time`, `Amount`, and the `Class` label (0 = valid, 1 = fraud).

---

## 🧠 Techniques Used

- Random Forest Classifier for binary classification
- Data preprocessing and cleaning
- Handling class imbalance (0.17% fraud cases)
- Feature correlation analysis
- Model evaluation using:
  - Accuracy
  - Precision
  - Recall
  - F1-score
  - Matthews Correlation Coefficient (MCC)
  - Confusion matrix visualization

---

## 📊 Results

| Metric      | Score     |
|-------------|-----------|
| Precision   | 98.7%     |
| Recall      | 79.6%     |
| F1-Score    | 88.1%     |
| Accuracy    | 99.96%    |
| MCC         | 0.88      |

> ⚠️ Note: Accuracy is high due to imbalance, but precision & recall are more meaningful here.

---

## 📌 File Structure

