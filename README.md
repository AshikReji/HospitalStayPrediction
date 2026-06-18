# Hospital Stay Duration Prediction

## Overview

Hospital stay duration is a critical factor in healthcare resource planning, patient management, and operational efficiency. Predicting the length of a patient's hospital stay can help healthcare providers optimize bed allocation, improve treatment planning, and reduce operational costs.

This project develops a Machine Learning model to predict the duration of a patient's hospital stay using demographic, admission, and clinical information. The solution leverages data preprocessing, feature engineering, and advanced regression techniques to generate accurate predictions.

---

## Problem Statement

Hospitals often face challenges in estimating how long a patient will remain admitted. Inaccurate estimates can lead to:

* Poor resource allocation
* Increased healthcare costs
* Bed occupancy issues
* Delays in patient care

The objective of this project is to build a predictive model that estimates patient hospital stay duration based on historical patient admission data.

---

## Dataset

The dataset contains patient admission records with features such as:

* Age
* Gender
* Type of Admission
* Severity of Illness
* Department
* Hospital Type
* Number of Visitors
* Available Extra Rooms
* Admission Information
* Other Patient and Hospital Attributes

### Target Variable

* **Stay Duration** (Length of Hospital Stay)

---

## Project Workflow

### 1. Data Understanding

* Explored dataset structure and feature distributions.
* Identified missing values and data quality issues.
* Analyzed categorical and numerical variables.

---

### 2. Exploratory Data Analysis (EDA)

Performed detailed analysis to identify patterns affecting hospital stay duration.

Key analyses included:

* Stay duration distribution
* Admission type analysis
* Severity of illness impact
* Age group analysis
* Department-wise patient distribution
* Correlation analysis of numerical features

Visualizations were created using Matplotlib and Seaborn.

---

### 3. Data Preprocessing

Data preparation steps included:

* Handling missing values
* Encoding categorical variables
* Feature scaling where required
* Outlier detection and treatment
* Data type conversions

---

### 4. Feature Engineering

Created meaningful features to improve predictive performance:

* Admission-related features
* Severity-based indicators
* Demographic transformations
* Encoded hospital characteristics

Feature engineering helped capture relationships that were not directly available in the raw dataset.

---

### 5. Model Development

Built an end-to-end Machine Learning pipeline using Scikit-learn.

Models evaluated:

* Logistic Regression
* Decision Tree
* Random Forest
* XGBoost

The pipeline automated:

* Data preprocessing
* Feature transformation
* Model training
* Prediction generation

---

### 6. Hyperparameter Tuning

Optimized model performance using:

* GridSearchCV
* Cross Validation

This ensured better generalization on unseen data.

---

### 7. Model Evaluation

Evaluation metrics used:

* Accuracy
* Precision
* Recall
* F1 Score

### Model Performance

| Model               | Accuracy |
| ------------------- | -------- |
| Logistic Regression | 61.06%   |
| Decision Tree       | 88.86%   |
| Random Forest       | 90.95%   |
| XGBoost             | 91.86%   |

**Best Performing Model:** XGBoost

The XGBoost model achieved the highest overall accuracy while effectively handling complex relationships within the dataset.

---

## Technologies Used

### Programming Language

* Python

### Libraries

* Pandas
* NumPy
* Scikit-learn
* XGBoost

### Visualization

* Matplotlib
* Seaborn

### Model Selection

* GridSearchCV
* Cross Validation

---

## Key Skills Demonstrated

* Data Cleaning
* Exploratory Data Analysis (EDA)
* Feature Engineering
* Machine Learning Pipelines
* Classification Modeling
* Hyperparameter Tuning
* Model Evaluation
* Predictive Analytics
* Healthcare Data Analysis

---

## Project Structure

```text
Hospital-Stay-Prediction/
│
├── data/
├── notebooks/
├── models/
├── app/
├── requirements.txt
├── README.md
└── hospital_stay_prediction.ipynb
```

---

## Future Improvements

* Incorporate additional patient health indicators.
* Apply advanced ensemble learning techniques.
* Deploy as a web application using Flask or Streamlit.
* Implement explainable AI techniques (SHAP/LIME).
* Integrate real-time hospital admission data.

---

## Conclusion

This project demonstrates the complete machine learning lifecycle, from data preprocessing and feature engineering to model optimization and evaluation. The developed solution provides valuable insights into factors affecting patient stay duration and can assist healthcare organizations in improving operational planning and patient management.

---

## Author

**Ashik Reji**
Data Science | AI Engineer

GitHub: [https://github.com/AshikReji](https://github.com/AshikReji)
LinkedIn: [https://linkedin.com/in/ashikreji/](https://linkedin.com/in/ashikreji/)
