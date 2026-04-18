# Diabetes Prediction using Support Vector Machine (SVM)

## 📖 Description
This project uses a machine learning approach to predict whether a person is diabetic or not based on medical attributes. The model is trained on a dataset containing features such as glucose level, BMI, age, and insulin levels. A Support Vector Machine (SVM) with a linear kernel is used for classification, achieving reliable performance on unseen data.

---

## 🔍 Overview
This project focuses on building a binary classification model to detect diabetes using patient health data. The workflow includes data preprocessing, feature scaling, model training, and evaluation.

---

## ⚙️ Technologies Used
- Python  
- NumPy  
- Pandas  
- Matplotlib  
- Seaborn  
- Scikit-learn  

---

## 📊 Dataset
The dataset contains **768 samples** with **8 input features**:

- Pregnancies  
- Glucose  
- Blood Pressure  
- Skin Thickness  
- Insulin  
- BMI  
- Diabetes Pedigree Function  
- Age  

**Target Variable:**
- Outcome (0 = Non-Diabetic, 1 = Diabetic)

---

## 🧠 Model
- Algorithm: Support Vector Machine (SVM)  
- Kernel: Linear  
- Data Scaling: StandardScaler  
- Train-Test Split: 80% training, 20% testing  

---

## 📈 Results
- Training Accuracy: **~77%**  
- Testing Accuracy: **~80%**

---

## 🚀 Features
- Data preprocessing and normalization  
- Model training and evaluation  
- Real-time prediction for new input data  

---

## ▶️ How to Run

1. Clone the repository:
```bash
git clone <your-repo-link>
cd diabetes-prediction
