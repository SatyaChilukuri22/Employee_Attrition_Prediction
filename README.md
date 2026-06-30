# Employee Attrition Prediction

## Project Overview

This project uses Machine Learning to predict whether an employee is likely to leave a company based on factors such as job satisfaction, monthly income, work-life balance, years at the company, and job role.

The objective is to help HR teams identify employees at risk of leaving so that appropriate retention strategies can be implemented.

---

## Dataset

**Dataset:** IBM HR Analytics Employee Attrition Dataset

- Total Records: 1,470 employees
- Target Variable: **Attrition**
  - Yes = Employee Left
  - No = Employee Stayed

---

## Project Tasks

- Data Loading & Exploration
- Data Cleaning & Preprocessing
- Exploratory Data Analysis (EDA)
- Feature Engineering
- Machine Learning Model Building
- Model Evaluation
- Data Visualization
- HR Business Insights & Recommendations

---

## Technologies Used

- Python
- Jupyter Notebook
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn

---

## Machine Learning Models

- Logistic Regression
- Random Forest Classifier
- Gradient Boosting Classifier

---

## Evaluation Metrics

The models were evaluated using:

- Precision
- Recall
- F1-Score
- ROC-AUC Score
- Confusion Matrix

Logistic Regression achieved the best overall performance on this dataset.

---

## Visualizations

The project includes:

- Attrition Rate by Department
- Attrition Rate by Job Role
- Monthly Income vs Attrition
- Confusion Matrix Heatmap
- Top 10 Feature Importances
- ROC Curve Comparison

---

## Project Structure

```
Employee_Attrition_Satya/
│
├── analysis.ipynb
├── WA_Fn-UseC_-HR-Employee-Attrition.csv
├── summary.pdf
├── README.md
└── charts/
    ├── chart1_attrition_rate.png
    ├── chart2_income_boxplot.png
    ├── chart3_confusion_matrix.png
    ├── chart4_feature_importance.png
    └── chart5_roc_curve.png
```

---

## Key Business Insights

- Sales department showed the highest employee attrition rate.
- Sales Representatives and Laboratory Technicians experienced the highest attrition among job roles.
- Employees with lower monthly income were more likely to leave.
- Poor work-life balance was associated with higher attrition.
- Employees in their early years with the company had a higher likelihood of leaving.

---


