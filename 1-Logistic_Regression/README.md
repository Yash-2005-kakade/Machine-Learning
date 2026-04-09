# 📊 Logistic Regression - Gym Premium Subscription Prediction

## 📌 Overview

This project predicts whether a gym member will purchase a premium subscription using a Logistic Regression model.

The model analyzes user behavior and lifestyle features to classify whether a user is likely to subscribe (1) or not (0).

---

## 🎯 Objective

- Predict premium subscription (0 = No, 1 = Yes)  
- Understand key factors influencing user decisions  
- Build an end-to-end classification pipeline  

---

## ⚙️ Workflow

1. Data Collection & Cleaning  
2. Handling Missing Values  
3. Encoding Categorical Features  
   - OneHotEncoder (Nominal data)  
   - OrdinalEncoder (Ordered data)  
4. Feature Scaling (StandardScaler)  
5. Model Training (Logistic Regression)  
6. Model Evaluation  

---

## 📊 Dataset Features

### 🔢 Numerical Features
- Age  
- Monthly_Income  
- Workout_Frequency  
- App_Usage_Time  
- Trial_Days_Used  

### 🔤 Categorical Features
- Preferred_Workout (Cardio, Strength, Yoga, etc.)  
- Diet_Type (Vegetarian, Non-Vegetarian, Vegan)  
- Fitness_Level (Beginner, Intermediate, Advanced)  
- Device_Type (iOS, Android)  

### 🎯 Target
- Subscription_Status (0 or 1)

---

## 📈 Model Performance

- Accuracy: 75%  
- Precision: 72%  
- Recall: 79%  
- F1 Score: 75%  

---

## 📊 Metrics Used

- Confusion Matrix  
- Classification Report  
- ROC Curve  

---

## 💡 Key Insights

- Higher app usage increases subscription probability  
- Workout frequency strongly influences user conversion  
- Engagement is more important than income  
- Model captures most subscribers (high recall)  
- Some false positives exist (moderate precision)  

---

## ⚠️ Challenges

- Balancing precision and recall  
- Handling categorical data effectively  
- Avoiding overfitting  

---

## 🛠️ Tech Stack

- Python 🐍  
- Pandas  
- NumPy  
- Scikit-learn  
- Matplotlib & Seaborn  

---

## 🙌 Conclusion

This project demonstrates how Logistic Regression can effectively classify user behavior and help businesses improve customer targeting and conversion strategies.
