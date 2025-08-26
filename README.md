
Employee Attrition Prediction & Insights 📉
Overview
This project uses data analytics and machine learning to predict employee attrition and identify the key factors that drive it. By analyzing a dataset from a large consulting firm, we've developed models and actionable insights to help HR teams create data-driven strategies for improving employee satisfaction and retention.

Problem Statement
Employee turnover is a significant challenge for any organization, leading to high costs and operational disruptions. The goal of this project was to help Salifort Motors' HR department understand the key drivers behind employee turnover by answering the question: "What's likely to make an employee leave the company?"

Data Description
The dataset contains 15,000 employee records, each with the following attributes:

satisfaction_level: Employee's satisfaction score.

last_evaluation: The score from their last performance evaluation.

number_project: The number of projects they are currently working on.

average_monthly_hours: The average number of hours worked per month.

tenure: Number of years the employee has been with the company.

work_accident: Binary variable (1 if they had a work accident, 0 otherwise).

left: Target variable; binary (1 if the employee left, 0 if they stayed).

promotion_last_5years: Binary (1 if they were promoted in the last 5 years, 0 otherwise).

department: The employee's department (e.g., Sales, HR, R&D).

salary: The salary level (e.g., Low, Medium, High).

Methodology
The project follows a standard data science pipeline:

1. Exploratory Data Analysis (EDA)
We performed extensive EDA to understand the data's structure, distributions, and relationships between variables.

2. Data Preprocessing
Cleaning: Addressed duplicate entries, outliers, and missing values.

Feature Engineering: Created new features where necessary and encoded categorical variables using ordinal and one-hot encoding for use in the models.

3. Model Building
We trained and evaluated three different machine learning models to find the best-performing one for our prediction task:

Logistic Regression

Random Forest Classifier

XGBoost Classifier

4. Model Evaluation
The models were evaluated using several key metrics to assess their performance:

Accuracy

Precision

Recall

F1-Score

ROC-AUC

Key Findings & Insights
Our analysis and models revealed several critical insights into employee attrition:

Satisfaction is Key: The satisfaction_level is the single strongest predictor of whether an employee will leave the company. Employees with low satisfaction are significantly more likely to resign.

Burnout Risk: Employees with a higher number_project, longer average_monthly_hours, and mid-to-high last_evaluation scores are at a higher risk of turnover, suggesting a correlation between overwork and attrition.

High-Performing Models: Both the Random Forest and XGBoost models performed exceptionally well, achieving over 98% accuracy with strong precision and recall for predicting leavers.

Salary & Department Matter: salary and department have a moderate impact on attrition, while a promotion_last_5years has a minimal effect.

Actionable Strategy: By focusing on managing employee workload and improving job satisfaction, HR can significantly reduce turnover.
