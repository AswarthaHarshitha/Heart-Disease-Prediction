# ❤️ Heart Disease Prediction

A Machine Learning project that predicts the likelihood of heart disease using clinical parameters. This system aims to assist in early diagnosis using a web-based interface powered by trained ML models.

---

## 📌 Overview

This project analyzes medical data to determine if a patient is likely to develop heart disease. It compares multiple machine learning algorithms and integrates the best-performing model into a simple web interface.

---

## 🔍 Features

- User-friendly web interface
- Predicts heart disease risk based on user input
- Compares multiple machine learning algorithms
- Visualizations for dataset insights and model evaluation
- Accuracy-focused model selection

---

## 🛠 Tech Stack

- **Language**: Python
- **ML Libraries**: scikit-learn, pandas, numpy, matplotlib, seaborn
- **Web Framework**: Flask
- **Deployment (Optional)**: Streamlit or Flask server

---

## 🧠 Algorithms Used

- Logistic Regression
- Decision Tree
- Random Forest
- K-Nearest Neighbors (KNN)
- Support Vector Machine (SVM)

---

## 📊 Dataset

- **File Used**: `heart_disease_data.csv`
- **Source**: [UCI Heart Disease Dataset (Cleveland)](https://archive.ics.uci.edu/ml/datasets/heart+Disease)
- **Description**: Contains 303 patient records with 14 attributes used to predict the presence of heart disease.
- **Common Attributes**:
  - `age` – Age in years  
  - `sex` – 1 = male; 0 = female  
  - `cp` – Chest pain type (0–3)  
  - `trestbps` – Resting blood pressure  
  - `chol` – Serum cholesterol in mg/dl  
  - `fbs` – Fasting blood sugar > 120 mg/dl (1 = true; 0 = false)  
  - `restecg` – Resting ECG results (0–2)  
  - `thalach` – Maximum heart rate achieved  
  - `exang` – Exercise-induced angina (1 = yes; 0 = no)  
  - `oldpeak` – ST depression induced by exercise  
  - `slope` – Slope of peak exercise ST segment  
  - `ca` – Number of major vessels colored by fluoroscopy (0–3)  
  - `thal` – 3 = normal; 6 = fixed defect; 7 = reversible defect  
  - `target` – 1 = presence of heart disease, 0 = absence  

---

## 🚀 Getting Started

### 1. Clone the repository
```bash
git clone https://github.com/AswarthaHarshitha/Heart-Disease-Prediction.git
cd Heart-Disease-Prediction
