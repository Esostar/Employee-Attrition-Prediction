# Employee Attrition Analysis
This repository contains the analysis and insights on employee attrition within an organization, using an HR employee dataset. The goal is to identify key factors contributing to employee attrition and provide actionable recommendations to mitigate it.

## Table of Contents

* Introduction
* Data Overview
* Analysis
* Exploratory Data Analysis (EDA)
* Feature Engineering
* Modeling
* Evaluation
* Recommendations
* Observations
* Conclusions
### Introduction
Employee attrition is a significant challenge for organizations, leading to loss of talent and increased recruitment costs. This analysis aims to understand the key drivers of employee attrition and provide recommendations to help organizations retain their employees.

### Data Overview
The dataset includes various attributes of employees, such as age, business travel, department, job satisfaction, and work-life balance. The target variable is Attrition, indicating whether an employee has left the organization.

### Analysis
Exploratory Data Analysis (EDA)
EDA involves understanding the distribution of data, checking for missing values, and visualizing relationships between variables.

### Feature Engineering
Categorical variables were encoded, and new features were created to improve the model's performance.

### Modeling
Several models were used to predict employee attrition, including:

Logistic Regression
Random Forest Classifier
Support Vector Machine (SVM) with RBF kernel
Evaluation
Models were evaluated based on accuracy, precision, recall, and F1 score. The Random Forest model and SVM with RBF kernel showed promising results.

### Recommendations
Manage Overtime: Employees working overtime have a higher attrition rate. Manage work more efficiently or provide incentives for overtime work.
Focus on Sales and Marketing Departments: These departments have high attrition rates. Improve incentive schemes to retain employees.
Increase Promotions and Salary Hikes: Frequent promotions and higher salary hikes can help retain employees.
Improve Work Environment: Enhance job satisfaction and environment satisfaction to reduce attrition.
Address Commute Issues: Provide shuttle services for employees traveling long distances.
Enhance Job Involvement: Improve growth opportunities and management styles to increase job involvement.
Support Younger Employees: Provide better support for new and inexperienced employees.
Offer Stock Options: Include stock options in compensation plans to motivate employees.
### Observations
Overtime is a significant driver of attrition.
Sales representatives and HR departments have higher attrition rates.
Low job involvement and job level correlate with higher attrition.
Employees with poor work-life balance are more likely to leave.
Higher income and better work environment satisfaction reduce attrition.
### Conclusions
Identified key factors involved in high attrition.
SVM with RBF kernel and Random Forest models provide good predictions.
HR departments can use these models to predict and mitigate employee attrition.
