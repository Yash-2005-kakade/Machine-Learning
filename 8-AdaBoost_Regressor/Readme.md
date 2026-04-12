# 🚀 Employee Salary Prediction using AdaBoost Regressor

## 📌 Project Overview
This project aims to predict employee salaries based on various features such as experience, performance, education, and work-related factors using Machine Learning techniques.

The focus of this project is to demonstrate how **ensemble learning (AdaBoost)** improves prediction accuracy compared to a single Decision Tree model.

---

## 🎯 Objectives
- Build a regression model to predict employee salary
- Compare Decision Tree and AdaBoost performance
- Apply hyperparameter tuning using GridSearchCV
- Evaluate models using MAE and R² Score

---

## 📊 Dataset Features
- Age  
- Experience_Years  
- Education_Level  
- Department  
- Num_Projects  
- Performance_Score  
- Certifications  
- Remote_Work  
- Overtime_Hours  
- Training_Hours  

🎯 Target: `Annual_Salary_Lakhs`

---

## ⚙️ Models Used

### 🌳 Decision Tree Regressor
- Baseline model for comparison

### 🚀 AdaBoost Regressor
- Ensemble method combining multiple weak learners
- Improves performance by focusing on errors

---

## 📈 Model Performance

| Model | MAE ↓ | R² Score ↑ |
|------|------|-----------|
| Decision Tree | 2.32 | 0.82 |
| AdaBoost (No Tuning) | 2.11 | 0.85 |
| AdaBoost (Tuned) 🔥 | **1.58** | **0.91** |

---

## 🔍 Key Insights
- AdaBoost significantly reduces prediction error compared to Decision Tree
- Hyperparameter tuning plays a crucial role in performance improvement
- Experience and performance score are major contributors to salary prediction

---

## 🧠 What I Learned
- Working of boosting algorithms
- Difference between weak learners and ensemble models
- Importance of model tuning
- Real-world regression problem solving

---

## 🛠️ Tech Stack
- Python
- Pandas
- NumPy
- Scikit-learn
- Matplotlib / Seaborn

---

## 🚀 Future Improvements
- Implement XGBoost / LightGBM
- Deploy model using Streamlit
- Add feature engineering
- Use real-world datasets

---

## 📌 Conclusion
AdaBoost outperformed the Decision Tree by a significant margin, achieving higher accuracy and lower error. This demonstrates the power of ensemble learning in handling complex regression problems.

---

## ⭐ If you like this project, give it a star!
