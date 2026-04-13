
# 📊 Sales Demand Forecasting using Machine Learning

## 🚀 Project Overview
This project focuses on predicting product sales (Quantity) using machine learning techniques. The goal is to build a reliable regression model that helps in demand forecasting and supports business decision-making.

---

## 🎯 Objectives
- Perform data preprocessing and feature engineering
- Train and compare multiple regression models
- Evaluate models using R² Score and MAE
- Apply hyperparameter tuning for performance improvement
- Select the best model based on accuracy and error

---

## 🧠 Dataset Features
- Invoice Date
- Delivery Date
- Product
- Region
- Quantity (Target)
- Stock
- Status
- Revenue (Dropped to avoid leakage)

---

## ⚙️ Data Preprocessing
- Converted date columns into datetime format
- Extracted features: day, month, delivery time
- Dropped unnecessary columns (Order_ID, dates, Revenue)
- Applied One-Hot Encoding for categorical variables

---

## 🤖 Models Used
- Linear Regression
- Decision Tree Regressor
- Random Forest Regressor
- AdaBoost Regressor
- XGBoost Regressor

---

## 📊 Model Performance

| Model            | R² Score | MAE  |
|------------------|--------|------|
| Linear Regression | 1.00   | 6.08 |
| Decision Tree     | 0.91   | 0.15 |
| Random Forest     | 0.94   | 0.24 |
| AdaBoost          | 0.96   | 0.20 |
| XGBoost (Tuned)   | **0.98** | **0.11** |

---

## 🔍 Key Insights
- Linear Regression showed misleading results due to high MAE
- Ensemble models outperformed simple models
- XGBoost achieved best performance after tuning

---

## 🏆 Final Conclusion
XGBoost emerged as the best model with highest accuracy and lowest error, making it suitable for real-world demand forecasting tasks.

---

## 🛠️ Tech Stack
- Python
- Pandas, NumPy
- Scikit-learn
- XGBoost

---

## 📌 Future Improvements
- Use larger datasets for better generalization
- Apply cross-validation
- Try advanced techniques like feature selection and stacking

---

## 🔗 Author
Yash Kakade
