# 🩺 Health-Insurance-Cost-Predictor-Project

A **machine learning–powered web app** built using **Streamlit**, designed to predict annual health insurance premium costs based on a user's **personal**, **lifestyle**, and **medical** factors.

---

## 🌟 Overview

The app intelligently classifies users into risk categories using trained ML models. It handles young users (≤ 25) and older users differently for higher prediction accuracy, with separate models and feature scaling.

---

## 🚀 Try the App

🔗 [Launch Credit Risk App] (https://health-insurance-cost-predictor-ml.streamlit.app/) 

---

## 🚀 Key Features

✅ Predicts annual **health insurance costs**  
✅ Uses **separate models** for different age groups (≤ 25 and > 25)  
✅ Robust **preprocessing & feature scaling** using `joblib`  
✅ Simple, interactive UI via **Streamlit**  
✅ Factors considered:

- Age, Income, Dependents  
- BMI Category, Smoking Habits  
- Marital & Employment Status  
- Insurance Plan & Region  
- Medical History & Genetic Risk  

---

## 🧠 Tech Stack

| Component       | Version     |
|----------------|-------------|
| Python          | 3.12        |
| Streamlit       | 1.37.1      |
| scikit-learn    | 1.5.1       |
| pandas / numpy  | 2.2.2 / 1.26.4 |
| XGBoost         | 3.0.2       |
| joblib          | 1.4.2       |

---

## 💡 Sample Input

Age: 30  
Gender: Male  
Region: Northwest  
Marital Status: Married  
BMI Category: Overweight  
Smoking Status: No Smoking  
Income in Lakhs: 6  
Insurance Plan: Silver  
Employment Status: Salaried  
Medical History: High Blood Pressure  
Genetical Risk: 0.4  
Number of Dependants: 2  

## 📊 Sample Output 
✅ Predicted Insurance Premium Cost: ₹42,300 




