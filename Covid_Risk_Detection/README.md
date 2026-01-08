# 🦠 COVID Risk Detection

## 📌 Project Overview
This project focuses on detecting the **risk level of COVID-19 infection** based on symptoms and health-related information.  
A **LightGBM (Light Gradient Boosting Machine)** model is used to classify individuals into different COVID risk categories.

---

## 🎯 Problem Statement
Given a person's symptoms and health indicators, predict the **COVID risk level** to assist in early detection and preventive decision-making.

This system can help in:
- Health risk assessment
- Early screening
- Medical prioritization

---

## 📊 Dataset
**File:** `covid_symptoms.csv`

### Sample Features:
- Fever
- Cough
- Breathing Difficulty
- Fatigue
- Body Pain
- Headache
- Sore Throat
- Age / Health Indicators

**Target Variable:**
- COVID Risk Level (Low / Medium / High)

---

## 🧠 Machine Learning Approach
- **Problem Type:** Classification  
- **Algorithm Used:** LightGBM Classifier (Ensemble Learning)

LightGBM is chosen for its:
- High performance
- Fast training
- Ability to handle complex feature interactions

---

## 🛠 Techniques Applied
- Data Cleaning & Preprocessing  
- Exploratory Data Analysis (EDA)  
- Feature Encoding  
- Model Training using LightGBM  
- Model Evaluation  

---

## 🧰 Tools & Technologies
- Python  
- Pandas  
- NumPy  
- Matplotlib  
- Seaborn  
- LightGBM  
- Scikit-learn  
- Jupyter Notebook  

---

## 📈 Results
The LightGBM model effectively classifies COVID risk levels with strong predictive performance, demonstrating the usefulness of ensemble learning in healthcare analytics.

---

## 📌 Conclusion
This project demonstrates how **machine learning models** can be applied to **healthcare risk prediction** problems and highlights the effectiveness of LightGBM for classification tasks.

---

## 🚀 Future Improvements
- Compare with Logistic Regression & Decision Tree
- Hyperparameter tuning
- Feature importance analysis
- Deploy as a web application for real-time risk prediction
