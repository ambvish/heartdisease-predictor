# 🩺 Heart Disease Prediction App

[Live Demo on Streamlit](https://your-app-link.streamlit.app)

## Overview
This project predicts the likelihood of heart disease using machine learning and patient medical data. It demonstrates the full ML pipeline — from data exploration and model training to deployment as an interactive web app using Streamlit.

## Dataset
- Source: UCI Heart Disease Dataset  
- Features: 13 clinical attributes (age, sex, chest pain type, blood pressure, cholesterol, max heart rate, etc.)  
- Target:  
  - 0 → No heart disease  
  - 1 → Heart disease present  

## ⚙ ML Pipeline
1. Data preprocessing & exploratory data analysis (EDA)  
2. Model training with Logistic Regression, SVM, and Random Forest  
3. Model evaluation (accuracy, F1-score, confusion matrix, ROC curve)  
4. Random Forest selected as the best model  
5. Saved as `heart_model.pkl` for deployment  
6. Interactive Streamlit app built for predictions  

##  Usage
Run locally:
```bash
streamlit run app.py
