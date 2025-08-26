
Employee Attrition Prediction & Insights
Overview
This project utilizes data analytics and machine learning to help HR teams predict employee attrition and understand the driving factors behind turnover. By analyzing employee survey and performance data from a large consulting firm, the goal is to develop actionable, data-driven strategies to improve satisfaction and retention rates.

Problem Statement
Employee turnover is expensive and disruptive. Salifort Motors’ HR department sought actionable insights from their employee dataset to answer: "What’s likely to make an employee leave the company?" This repository provides models and visualizations to identify and address these risks.

Data Description
The dataset contains 15,000 employee records, each described by:

satisfaction_level

last_evaluation

number_project

average_monthly_hours

tenure (years at company)

work_accident (binary)

left (target variable: left or stayed)

promotion_last_5years (binary)

department (categorical)

salary (categorical)

Methodology
Exploratory Data Analysis (EDA)

Data Cleaning (duplicates, outliers, missing values, encoding)

Feature Engineering (ordinal and one-hot encoding)

Model Building:

Logistic Regression

Random Forest Classifier

XGBoost Classifier

Model Evaluation (accuracy, precision, recall, F1-score, ROC-AUC)

Data Visualizations (boxplots, bar charts, pie charts, heatmaps)

Key Findings
Satisfaction level is the strongest predictor of attrition (low satisfaction employees likely to leave).

Employees with more projects, longer working hours, and mid/high evaluation scores show increased turnover risk.

Random Forest and XGBoost models achieved 98%+ accuracy with strong recall and precision for predicting leavers.

Salary and department have moderate importance; promotion history has minimal effect.

Managing workload and satisfaction can significantly reduce turnover.

How to Use
All code and notebooks are provided; data is loaded automatically for analysis and model training.

Execute notebooks in sequence for EDA, model building, and visualization.

Review output visualizations and feature importance for actionable HR insights.

Recommendations
Focus on regular employee feedback and satisfaction tracking.

Monitor and optimize project assignment and monthly work hours.

Improve career growth and promotion transparency.

Use model outputs for targeted retention strategies across departments and salary bands.

Ethical Considerations
Employee privacy and data security are strictly maintained.

All analysis and recommendations aim for fairness, transparency, and compliance with discrimination policies.

Resources
Python (Pandas, NumPy, Seaborn, Matplotlib, Scikit-learn, XGBoost)

GridSearchCV for hyperparameter tuning

Kaggle (data source)

Data science best practices
