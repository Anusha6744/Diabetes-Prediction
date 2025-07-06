# Diabetes Prediction Using Machine Learning

# Project Overview
This project aims to predict whether a patient has diabetes based on diagnostic features such as glucose level, BMI, age, etc. Multiple machine learning models were applied and compared, including Logistic Regression, Random Forest, and XGBoost.

## Dataset
- Source: [Pima Indians Diabetes Dataset - Kaggle](https://www.kaggle.com/uciml/pima-indians-diabetes-database)
- 768 samples, 8 features + binary target (`Outcome`)

## Problem Statement
Predict whether a person is diabetic (`Outcome = 1`) or not (`Outcome = 0`) using health-related data.

##  Tools & Technologies
- Python, Pandas, NumPy
- Seaborn & Matplotlib for visualization
- Scikit-learn for ML models
- XGBoost
- Jupyter Notebook

##  Workflow
1. **Exploratory Data Analysis (EDA)**
   - Heatmaps, countplots, and feature distributions
2. **Preprocessing**
   - Handling missing values
   - Feature scaling using StandardScaler
3. **Modeling**
   - Logistic Regression
   - Random Forest
   - XGBoost
4. **Evaluation**
   - Accuracy, Confusion Matrix, Classification Report
   - Cross-validation
5. **Feature Importance**
   - Visualized with bar chart
   - Identified top predictive features

##  Results
| Model              | Accuracy |
|--------------------|----------|
| Logistic Regression| 75%      |
| Random Forest      | 72%      |
| XGBoost            | 72%      |
| Best (CV)          | 76%      |

## Key Learnings
- Importance of cross-validation for reliable metrics
- Dealing with class imbalance improves performance
- Feature importance can help in interpretation

## 📁 Project Structure
