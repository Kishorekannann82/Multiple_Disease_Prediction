# 🩺 Multiple Disease Prediction System Using Machine Learning

This Streamlit web application predicts the likelihood of six different diseases using user-provided medical data. Each disease has its own trained Machine Learning model. It is designed as an easy-to-use health screening tool.

---

## 🚀 Live Demo

👉 **[Try the App Now](https://kishorelytics-multiple-disease-prediction.streamlit.app/)**  
*(Hosted via Streamlit Community Cloud)*

---

## 🔍 Diseases Covered

| Disease | Model Used | Algorithm | Accuracy (approx.) |
|--------|-------------|-----------|---------------------|
| Diabetes | `diabetes.pkl` | Logistic Regression | 76% |
| Heart Disease | `heart.pkl` | Logistic Regression | 84% |
| Parkinson’s | `Parkinsons.pkl` | SVM (Support Vector Machine) | 88% |
| Kidney Disease | `kidney.pkl` | Logistic Regression | 94% |
| Liver Disease | `liver.pkl` | SVM (Support Vector Machine) | 75% |
| Breast Cancer | `breast_cancer.pkl` | Logistic Regression | 97% |

Each model was trained on public datasets with proper preprocessing and evaluation.

---

## 🧠 Machine Learning Details

### 📌 1. Diabetes
- **Dataset**: PIMA Indians Diabetes Dataset (Kaggle/UCI)
- **Features**: Glucose, Blood Pressure, BMI, Age, etc.
- **Model**: Logistic Regression
- **Why**: Performs well on binary classification tasks with limited features.

### 📌 2. Heart Disease
- **Dataset**: Cleveland Heart Disease dataset (UCI)
- **Features**: Age, Cholesterol, Resting BP, ECG, etc.
- **Model**: Logistic Regression
- **Why**: Easy to interpret and sufficient for binary heart disease prediction.

### 📌 3. Parkinson’s Disease
- **Dataset**: UCI Parkinson’s dataset
- **Features**: Voice frequency and jitter values
- **Model**: Support Vector Machine (SVM)
- **Why**: SVM handles high-dimensional voice feature space well.

### 📌 4. Kidney Disease
- **Dataset**: Chronic Kidney Disease (CKD) dataset (UCI)
- **Features**: Albumin, Blood Urea, Serum Creatinine, etc.
- **Model**: Logistic Regression
- **Why**: Clear binary classification, handles missing data well with preprocessing.

### 📌 5. Liver Disease
- **Dataset**: Indian Liver Patient Dataset (UCI)
- **Features**: Age, Gender, Bilirubin, Enzyme levels
- **Model**: Support Vector Machine (SVM)
- **Why**: Performs well with smaller datasets and non-linear decision boundaries.

### 📌 6. Breast Cancer
- **Dataset**: Wisconsin Breast Cancer dataset (UCI)
- **Features**: Radius, Texture, Smoothness, Concavity, etc.
- **Model**: Logistic Regression
- **Why**: High performance with minimal tuning.

---

## 📂 Project Structure

📁 multiple-disease-prediction/
├── main.py # Main Streamlit app
├── diabetes.pkl # Trained model files
├── heart.pkl
├── kidney.pkl
├── liver.pkl
├── Parkinsons.pkl
├── breast_cancer.pkl
├── *.csv # Dataset files
├── *.ipynb # Model training notebooks
├── requirements.txt # Required libraries
└── README.md # This file

🧾 Requirements
streamlit
streamlit-option-menu
pandas
numpy
scikit-learn
matplotlib
seaborn


📈 Model Building Process
Data Cleaning & Preprocessing

Exploratory Data Analysis (EDA)

Feature Selection

Model Training & Evaluation (train/test split)

Model Saving using pickle

Each .ipynb file corresponds to training and evaluation of one disease model.

🌐 Deployment
App deployed using Streamlit Community Cloud.

Models are loaded from .pkl files in the app directory.

No database/backend required – pure Python-based UI.

🙋‍♂️ Author
Kishore Kannan N


Live Demo:https://kishorelytics-multiple-disease-prediction.streamlit.app/



