# Student Performance Prediction using Machine Learning

## Overview

Student academic performance is influenced by multiple factors including study habits, attendance, family background, and previous academic achievements. This project applies Machine Learning techniques to analyze these factors and predict students' final grades (**G3**).

The project includes data preprocessing, exploratory data analysis (EDA), feature engineering, model training, and performance evaluation to build a reliable grade prediction system.

---

## Objectives

* Analyze factors influencing student academic performance.
* Explore relationships between academic, demographic, and behavioral attributes.
* Identify the most important features affecting final grades.
* Build a predictive Machine Learning model for grade prediction.
* Evaluate model performance using regression metrics.
* Generate insights that can support educational decision-making.

---

## Dataset Information

The dataset contains student-related information including:

* Demographic Information
* Family Background
* Study Time
* Attendance / Absences
* Educational Support
* Social Factors
* Previous Academic Performance
* Final Grade (G3)

### Target Variable

* **G3** – Final Student Grade

---

## Tools & Technologies

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Scikit-Learn
* Jupyter Notebook

---

## Data Preprocessing

The following preprocessing steps were performed:

* Data Cleaning
* Feature Encoding
* Handling Categorical Variables
* Feature Selection
* Train-Test Split

---

## Machine Learning Model

### Model Used

* Linear Regression

### Model Performance

| Metric                    | Score     |
| ------------------------- | --------- |
| R² Score                  | **0.853** |
| Mean Absolute Error (MAE) | **0.755** |

### Interpretation

The model explains approximately **85.3%** of the variance in student grades and predicts final scores with an average error of less than **1 mark**, indicating strong predictive performance.

---

## Sample Visualizations

### Actual vs Predicted Grades

![Actual vs Predicted Grades](images/actual_vs_predicted.png)

This visualization compares actual student grades with model predictions, demonstrating how closely the model estimates final performance.

---

### Feature Importance Analysis

![Feature Importance](images/feature_importance.png)

Feature importance analysis highlights the variables that contribute most significantly to predicting student grades and provides insights into the factors associated with academic success.

---

## Key Findings

* Previous academic performance is the strongest predictor of final grades.
* Students with consistent study habits generally perform better.
* Attendance and absenteeism have a measurable impact on academic outcomes.
* Multiple factors collectively influence student performance rather than any single variable.
* The Linear Regression model achieved strong predictive accuracy with an R² score of 0.853.

---

## Business / Educational Impact

The insights generated from this analysis can help:

* Identify students at risk of poor academic performance.
* Support data-driven educational interventions.
* Improve academic monitoring and support systems.
* Assist institutions in understanding factors affecting student success.

---

## Project Structure

```text
Student-Performance-Prediction/
│
├── Student-performance-ML.ipynb
├── student-mat.csv
├── README.md
├── requirements.txt
│
└── images/
    ├── actual_vs_predicted.png
    └── feature_importance.png
```

---

## Future Improvements

* Hyperparameter Tuning
* Random Forest Regression
* XGBoost Implementation
* Streamlit Web Application
* Interactive Student Analytics Dashboard
* Student Risk Prediction System

---

## Author

**Srushti Chordiya**

Aspiring Data Scientist | Machine Learning Enthusiast | B.Tech Student
