# ❤️ Heart Disease Prediction Web Application

## 📌 Project Overview

This project is a Machine Learning-based web application that predicts the risk of heart disease using medical parameters. The model is built using the K-Nearest Neighbors (KNN) algorithm and deployed using Streamlit for real-time predictions.

The application allows users to input clinical details and instantly receive a prediction indicating whether they are at low or high risk of heart disease.

---

## 🚀 Features

- Interactive and user-friendly Streamlit interface
- Real-time prediction
- Pre-trained KNN classification model
- Feature scaling using StandardScaler
- Saved feature column alignment for consistent predictions
- Clean and simple UI design

---

## 🧠 Machine Learning Details

- Algorithm Used: K-Nearest Neighbors (KNN)
- Problem Type: Binary Classification
- Preprocessing:
  - Feature scaling using StandardScaler
  - Column alignment using saved `columns.pkl`
- Model File: `KNN_heart.pkl`
- Scaler File: `scaler.pkl`
- Columns File: `columns.pkl`

---

## 📊 Input Features

The model uses the following medical parameters:

- Age  
- Sex  
- Chest Pain Type  
- Resting Blood Pressure  
- Cholesterol  
- Fasting Blood Sugar  
- Resting ECG  
- Maximum Heart Rate Achieved  
- Exercise-Induced Angina  
- Oldpeak (ST Depression)  
- ST Slope  

---

## ⚙️ How It Works

1. User enters medical details in the Streamlit form.
2. Input data is converted into a Pandas DataFrame.
3. Feature columns are aligned using the saved `columns.pkl`.
4. Data is scaled using the saved `StandardScaler`.
5. The KNN model predicts:
   - 0 → Low Risk
   - 1 → High Risk
6. Result is displayed instantly on the interface.

---

## 🛠 Tech Stack

- Python  
- Streamlit  
- Scikit-learn  
- Pandas  
- NumPy  
- Pickle  

---
