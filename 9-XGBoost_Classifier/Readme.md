# 📊 Customer Churn Prediction using XGBoost & AdaBoost

## 📌 Problem Statement
Customer retention is a critical challenge for businesses. This project aims to predict whether a customer will churn based on various features such as usage patterns, subscription type, and demographics.

---

## 🎯 Objectives
- Build a classification model to predict customer churn
- Compare performance of:
  - XGBoost (Before Tuning)
  - XGBoost (After Tuning)
  - AdaBoost Classifier
- Evaluate models using multiple metrics

---

## ⚙️ Tech Stack
- Python
- Pandas
- NumPy
- Scikit-learn
- XGBoost

---

## 🧹 Data Preprocessing
- Handled missing values using:
  - Median (numerical features)
  - Mode (categorical features)
- Encoded categorical variables using Label Encoding
- Performed train-test split (80-20)

---

## 🤖 Models Used

### 🔹 XGBoost (Baseline)
- Accuracy: **87%**
- Strong performance with balanced predictions

### 🔹 XGBoost (Tuned)
- Accuracy: **85.5%**
- Improved generalization but slightly lower than baseline

### 🔹 AdaBoost
- Accuracy: **84%**
- Competitive but less stable compared to XGBoost

---

## 📊 Evaluation Metrics
- Accuracy
- Precision
- Recall
- F1-Score

---

## 📈 Results Comparison

| Model                | Accuracy |
|---------------------|---------|
| XGBoost (Baseline)  | 0.87    |
| XGBoost (Tuned)     | 0.855   |
| AdaBoost            | 0.84    |

---

## 🧠 Key Insights
- XGBoost outperformed AdaBoost in all cases
- Hyperparameter tuning does not always guarantee better performance
- Default XGBoost model was already well-optimized for this dataset

---

## 🚀 Conclusion
XGBoost proved to be the most effective model for predicting customer churn. While tuning improved model understanding, the baseline model achieved the best performance, highlighting the robustness of XGBoost.

---

## 🔮 Future Improvements
- Use advanced hyperparameter tuning (RandomizedSearchCV)
- Handle class imbalance using SMOTE
- Deploy using Streamlit

---

## 👨‍💻 Author
Yash Kakade
