# 🫀 Heart Disease Prediction App
### Built by Priyal

A machine learning web application that predicts the risk of heart disease based on clinical parameters. Built using **KNN (K-Nearest Neighbors)** algorithm and deployed with **Streamlit**.

---

## 🌐 Live Demo
> Run locally using the steps below or deploy on Streamlit Cloud.

---

## 📌 About the Project

This app takes 11 clinical inputs from the user and predicts whether the person is at **Low Risk** or **High Risk** of heart disease. The model was trained on a real-world heart disease dataset and achieves reliable accuracy using the KNN classifier.

---

## 🧠 How It Works

1. User fills in clinical details through an interactive web form
2. Input data is preprocessed and scaled using a trained **StandardScaler**
3. The **KNN model** makes a prediction
4. Result is displayed as **Low Risk ✅** or **High Risk ⚠️**

---

## 📋 Input Features

| Feature | Description |
|---|---|
| Age | Age of the patient (18–100) |
| Sex | Male (M) or Female (F) |
| Chest Pain Type | ATA, NAP, TA, or ASY |
| Resting Blood Pressure | Blood pressure in mm HG |
| Cholesterol | Serum cholesterol in mg/dL |
| Fasting Blood Sugar | > 120 mg/dL (0 = No, 1 = Yes) |
| Resting ECG | Normal, ST, or LVH |
| Max Heart Rate | Maximum heart rate achieved |
| Exercise-Induced Angina | Yes (Y) or No (N) |
| Oldpeak | ST depression induced by exercise |
| ST Slope | Up, Flat, or Down |

---

## 🛠️ Tech Stack

- **Python** — Core programming language
- **Scikit-learn** — KNN model and StandardScaler
- **Pandas & NumPy** — Data preprocessing
- **Streamlit** — Web app framework
- **Joblib** — Model serialization

---

