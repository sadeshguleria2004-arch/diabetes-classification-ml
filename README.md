# Diabetes Classification using Machine Learning

## 📌 Project Description
This project builds and evaluates machine learning models to classify patients as **Diabetic** or **Not Diabetic** using a diabetes dataset from Kaggle.

## 📊 Dataset
- Source: Kaggle
- Dataset: Diabetes Dataset for Classification
- Target variable: Outcome  
  - 0 → Not Diabetic  
  - 1 → Diabetic  

## 🧠 Models Used
- K-Nearest Neighbors (KNN)
- Logistic Regression (liblinear solver)
- Logistic Regression (lbfgs solver)

## 🔀 Methodology
- Train–Validation–Test split (70%–15%–15%)
- Feature scaling using StandardScaler
- Model evaluation using accuracy, confusion matrix, and classification report
- Patient-wise prediction output on unseen test data

## ✅ Results
Logistic Regression with the **lbfgs solver** showed the best overall performance and generalization.

## 🚀 Tools & Libraries
- Python
- Pandas
- Scikit-learn
- Google Colab
