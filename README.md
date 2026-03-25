📌 Overview
This project aims to predict whether a user will subscribe to a fitness app using Machine Learning.
A Logistic Regression model is built with a complete preprocessing pipeline to handle both categorical and numerical features.
🎯 Objectives
Predict user subscription behavior (0 = No, 1 = Yes)
Understand key factors influencing subscriptions
Build an end-to-end ML pipeline
Evaluate model performance using multiple metrics
📊 Dataset Features
🔢 Numerical Features
Age
Monthly_Income
Workout_Frequency
App_Usage_Time
Trial_Days_Used
🔤 Categorical Features
Preferred_Workout (Cardio, Strength, Yoga, etc.)
Diet_Type (Vegetarian, Non-Vegetarian, Vegan)
Fitness_Level (Beginner, Intermediate, Advanced)
Device_Type (iOS, Android)
🎯 Target
Subscription_Status (0 or 1)
⚙️ Tech Stack
Python 🐍
Pandas & NumPy
Scikit-learn
Matplotlib & Seaborn
🔄 Workflow
Data Collection & Cleaning
Feature Encoding
OneHotEncoder (Nominal data)
OrdinalEncoder (Ordered data)
Feature Scaling (StandardScaler)
Model Building (Logistic Regression)
Model Evaluation
Visualization
🏗️ Pipeline Structure
ColumnTransformer used for preprocessing
Pipeline integrates preprocessing + model
Ensures clean and reproducible workflow
📈 Model Evaluation
Accuracy: 75%
Precision: 72%
Recall: 79%
F1 Score: 75%
📊 Metrics Used:
Confusion Matrix
Classification Report
ROC Curve
🔍 Key Insights
Higher app usage time increases subscription chances
Workout frequency strongly influences user conversion
Engagement is more important than income
Model captures most subscribers (high recall)
Some false positives exist (moderate precision)
Balanced dataset improved model reliability
