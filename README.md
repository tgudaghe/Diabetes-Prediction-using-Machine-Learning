## 📁 Project Overview

This notebook is part of the final milestone for the course **DSC 670 – Advanced Topics in Data Science**. The focus of this milestone is to apply predictive modeling techniques to identify and assess the likelihood of diabetes in patients based on health-related features.

## 🎯 Objective

- Develop and evaluate machine learning models for predicting diabetes.
- Compare multiple algorithms for performance.
- Address class imbalance and model interpretability.
- Provide actionable insights from data exploration and model outputs.

## 📊 Dataset

- **Source:** Pima Indians Diabetes Dataset from Kaggle/UCI
- **Features:** Includes columns such as `Pregnancies`, `Glucose`, `BloodPressure`, `SkinThickness`, `Insulin`, `BMI`, `DiabetesPedigreeFunction`, `Age`, and `Outcome`.
- **Target:** `Outcome` (0 = Non-diabetic, 1 = Diabetic)

## 🛠️ Techniques Used

- **Data Preprocessing:** Null value handling, outlier detection, scaling
- **Exploratory Data Analysis (EDA):** Visualizations, correlation heatmaps
- **Modeling Techniques:** 
  - Logistic Regression
  - Random Forest
  - XGBoost
  - K-Nearest Neighbors
- **Evaluation Metrics:**
  - Accuracy
  - Precision, Recall, F1 Score
  - ROC-AUC
- **Cross-validation and GridSearch for tuning**


## 🧪 Results Summary

- Gradient Boost outperformed other models based on accuracy and AUC.
- Logistic Regression provided explainability, while Random Forests and XGBoost gave higher performance.
- Feature importance was visualized and interpreted to identify key risk factors.

## 📦 Dependencies

Run the notebook in an environment with the following Python libraries:

```bash
pandas
numpy
matplotlib
seaborn
scikit-learn
xgboost
