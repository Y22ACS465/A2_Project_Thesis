# Diabetes Prediction Using Data Analytics and Machine Learning Algorithms
# Authors
  - J. Kalyani (Y22ACS465)
  - H. Likitha (Y22ACS463)
  - M. Karthik (Y22ACS495)
  - M. Sujata (L23ACS609)
# Implementation
Diabetes Prediction Using Data Analytics and Machine Learning Algorithms Implementation:https://github.com/Y22ACS465/Diabetes-Prediction-Using-Data-Analytics-and-Machine-Learning-Algorithms.git
## Overview
This project presents an intelligent healthcare application that predicts diabetes risk using Machine Learning algorithms and Data Analytics techniques.  

The system analyzes user-provided clinical and demographic data to estimate the probability of diabetes and classifies the risk into **LOW, MEDIUM, and HIGH categories**.  

In addition to prediction, the application integrates **Explainable Artificial Intelligence (XAI)** using SHAP to provide transparency, along with **clinical interpretation and personalized health recommendations** through an interactive Streamlit dashboard.
## Key Features
  - Machine Learning-based Diabetes Prediction  
  - Risk Classification (Low / Medium / High)  
  - Explainable AI using SHAP  
  - Clinical Interpretation   
  - Personalized Health Recommendations  
  - Diet & Lifestyle Suggestions  
  - Interactive Web Dashboard (Streamlit)  
  - Feature Importance Visualization
## System Architecture
The Diabetes Prediction System follows a structured pipeline to process user input and generate accurate, interpretable results:
- **User Input**  
   The user enters clinical details such as age, BMI, HbA1c level, blood glucose level, hypertension, heart disease, gender, and smoking history.
- **Data Preprocessing**  
   Input data is validated, encoded, and scaled to match the format required by the trained machine learning model.
- **Model Prediction**  
   The processed data is passed to the trained ML model, which predicts the probability of diabetes.
- **Risk Classification**  
   The predicted probability is categorized into LOW Risk,MEDIUM Risk,HIGH Risk  
- **SHAP Explainability**  
   SHAP (Explainable AI) analyzes how each feature contributes to the prediction and identifies key risk factors.
- **Visualization**  
   Graphs and plots are generated to represent feature importance and model insights.
- **Clinical Interpretation**  
   The system generates a detailed explanation of the patient’s health condition based on input values.
- **Personalized Recommendations**  
   Based on risk level, the system suggests diet plans, lifestyle changes, and medical advice.
## Tech Stack
  - **Programming Language:** Python  
  - **Machine Learning:** Scikit-learn, XGBoost  
  - **Web Framework:** Streamlit  
  - **Data Processing:** Pandas, NumPy  
  - **Explainability:** SHAP  
  - **Visualization:** Matplotlib, Plotly  
  - **Model Handling:** Joblib
## Model Details
The Diabetes Prediction System uses supervised machine learning algorithms to analyze patient data and predict diabetes risk.
###  Algorithms Used
- **Logistic Regression** (Linear Classification Model) 
- **Decision Tree** (Rule-Based Model)  
- **Random Forest** (Ensemble Learning Model) 
- **XGBoost** (Gradient Boosting Model)
**Selected Model:** XGBoost Classifier — chosen based on highest accuracy, better generalization, and superior performance across evaluation metrics (Precision,     Recall, F1-Score) compared to other models.
# How to Run
### 1. Install dependencies
```
pip install -r requirements.txt
```

### 2. Run dashboard
```
streamlit run dashboard.py
```

---
