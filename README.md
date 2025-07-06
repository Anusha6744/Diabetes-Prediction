# Diabetes Prediction Using Machine Learning

This project predicts whether a patient has diabetes based on diagnostic health data. It uses supervised machine learning algorithms like **Logistic Regression**,**XG Boost**and **Random Forest**, along with **cross-validation** for performance evaluation.

---

## Dataset

- **Source**: [Pima Indians Diabetes Dataset on Kaggle](https://www.kaggle.com/datasets/uciml/pima-indians-diabetes-database)
- **Records**: 768 patients
- **Features**: 8 input features + 1 target (`Outcome`)

---

## Objective

To build a machine learning model that can accurately classify patients as **diabetic** (`1`) or **non-diabetic** (`0`) based on medical data.

---

## Technologies Used

- Python
- Pandas, NumPy
- Seaborn, Matplotlib
- Scikit-learn (Logistic Regression, Random Forest, Cross-validation)
- StandardScaler

---

##  Project Steps

### 1. **Data Exploration**
- Displayed head, info, and descriptive statistics.
- Checked for missing values or anomalies.

### 2. **Data Visualization**
- Plotted class distributions using `sns.countplot`.
- Generated a correlation heatmap for feature analysis.

### 3. **Preprocessing**
- Scaled the features using `StandardScaler`.
- Split the data into training and test sets.

### 4. **Model Training**
- Trained **Logistic Regression**, **Random Forest**, **XG Boost**
- Evaluated each using:
  - Accuracy
  - Confusion Matrix
  - Classification Report

### 5. **Cross-Validation**
- Performed 5-fold cross-validation to assess generalization.
- Achieved cross-validated accuracy of:
  - **Logistic Regression**: ~77%
  - **Random Forest**: ~76%
  -  **XG Boost**: ~74%

### 6. **Feature Importance**
- Used Random Forest to identify key features:
  - Glucose
  - BMI
  - Age

---

## 📈 Results

| Model              | Accuracy (Test Set) | Cross-Validated Accuracy |
|--------------------|--------------------|---------------------------|
| Logistic Regression| 75%                | 77%                       |
| Random Forest      | 72%                | 76%                       |
| XG Boost           | 72%                | 74%
---

## 📌 Insights

- Logistic Regression slightly outperformed Random Forest and XG Boost in both test and cross-validation.
- `Glucose`, `BMI`, and `Age` are the most influential features in predicting diabetes.
- Data preprocessing and feature scaling significantly improved model performance.

---




