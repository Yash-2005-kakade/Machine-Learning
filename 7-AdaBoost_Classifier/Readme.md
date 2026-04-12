# 🚀 Customer Churn Prediction using AdaBoost

## 📌 Overview
This project focuses on predicting customer churn using the AdaBoost Classifier. It demonstrates how boosting improves the performance of weak learners by iteratively correcting misclassified samples.

---

## 🎯 Problem Statement
Customer churn prediction is a critical business problem where companies aim to identify customers likely to leave. Due to complex and non-linear customer behavior, traditional models often struggle to achieve high accuracy.

---

## 🎯 Objectives
- Predict customer churn using machine learning  
- Understand boosting and ensemble learning  
- Handle categorical and numerical data  
- Compare AdaBoost with Decision Tree  
- Evaluate model performance  

---

## 📊 Dataset Features
- Age  
- Monthly Charges  
- Tenure  
- Support Calls  
- Contract Type  
- Internet Service  
- Payment Method  
- Region  
- Device Type  
- Churn (Target Variable)  

---

## ⚙️ Technologies Used
- Python  
- Pandas  
- NumPy  
- Scikit-learn  
- Matplotlib  
- Seaborn  

---

## 🔧 Project Workflow
1. Data Loading  
2. Exploratory Data Analysis (EDA)  
3. Data Preprocessing (Encoding categorical features)  
4. Train-Test Split  
5. Model Training (Decision Tree & AdaBoost)  
6. Model Evaluation  
7. Performance Comparison  

---

## 🤖 Models Used
- Decision Tree Classifier  
- AdaBoost Classifier (with Decision Tree as base estimator)

---

## 📈 Results

| Model | Accuracy |
|------|---------|
| Decision Tree | 72% |
| AdaBoost | 87% |

👉 AdaBoost significantly improved performance by reducing errors iteratively.

---

## 📊 Evaluation Metrics
- Accuracy Score  
- Classification Report  
- Confusion Matrix  

---

## 💡 Key Learnings
- Boosting improves weak learners  
- Importance of handling categorical data  
- Impact of noise on model performance  
- Real-world application of churn prediction  

---

## 🚀 Future Improvements
- Hyperparameter tuning  
- Compare with Random Forest & XGBoost  
- Deploy model using Flask or Streamlit  

---

## 🧠 Conclusion
The AdaBoost model significantly outperformed the standalone Decision Tree, improving accuracy from 72% to 87%. This demonstrates the effectiveness of boosting in enhancing weak learners by focusing on misclassified samples and iteratively reducing errors.

The model achieved balanced precision and recall for both churn and non-churn classes, making it reliable for real-world applications. With a high recall for churn prediction, the model is particularly useful for identifying customers at risk, enabling proactive retention strategies.

---

## 🙌 Author
**Yash Kakade**  
Aspiring Data Scientist | AI/ML Enthusiast  

---
