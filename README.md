---
title: Diabetes Prediction App
description: Predict diabetes using ML models with a clean Streamlit UI.
tags: [Python, Streamlit, Machine Learning, Healthcare, Project]
---

# 🩺 Diabetes Prediction App

A lightweight and accurate **ML-powered web app** to predict whether a person is diabetic based on clinical inputs like glucose, BMI, age, and insulin levels. Built for healthcare use cases with end-to-end model training, evaluation, and deployment.

---

## 🚀 Features

- 🔬 Predict diabetes using real patient attributes
- ⚖️ Balanced dataset with **SMOTE**
- 🧠 Compared multiple models (LogReg, RF, XGBoost)
- 📊 Evaluation: Accuracy, Confusion Matrix, AUC
- 🧪 Hyperparameter tuning with **GridSearchCV**
- 💻 Deployed via **Streamlit**

---

## 🛠 Tech Stack

<div align="center">

<img src="https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white"/>
<img src="https://img.shields.io/badge/Pandas-150458?style=for-the-badge&logo=pandas&logoColor=white"/>
<img src="https://img.shields.io/badge/Numpy-013243?style=for-the-badge&logo=numpy&logoColor=white"/>
<img src="https://img.shields.io/badge/Scikit--Learn-F7931E?style=for-the-badge&logo=scikitlearn&logoColor=white"/>
<img src="https://img.shields.io/badge/Streamlit-FF4B4B?style=for-the-badge&logo=streamlit&logoColor=white"/>
<img src="https://img.shields.io/badge/Matplotlib-FF9999?style=for-the-badge&logo=matplotlib&logoColor=black"/>
<img src="https://img.shields.io/badge/XGBoost-EC3E29?style=for-the-badge&logo=xgboost&logoColor=white"/>
<img src="https://img.shields.io/badge/SMOTE-BALANCE-green?style=for-the-badge"/>
<img src="https://img.shields.io/badge/GridSearchCV-TUNING-blue?style=for-the-badge"/>

</div>

---

## 📁 Project Structure

📦diabetes-prediction-app
┣ 📜app.py → Streamlit frontend
┣ 📜model_training.ipynb → Training & preprocessing
┣ 📜final_model.pkl → Saved trained model
┣ 📜requirements.txt → Dependencies
┗ 📊diabetes_dataset.csv → Input dataset
