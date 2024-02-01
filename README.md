# Employee Attrition Prediction

[![Python](https://img.shields.io/badge/python-3670A0?style=for-the-badge&logo=python&logoColor=ffdd54)](https://www.python.org)
[![NumPy](https://img.shields.io/badge/numpy-%23013243.svg?style=for-the-badge&logo=numpy&logoColor=white)](https://numpy.org)
[![Pandas](https://img.shields.io/badge/pandas-%23150458.svg?style=for-the-badge&logo=pandas&logoColor=white)](https://pandas.pydata.org) 
[![scikit-learn](https://img.shields.io/badge/scikit--learn-%23F7931E.svg?style=for-the-badge&logo=scikit-learn&logoColor=white)](https://scikit-learn.org/stable)
[![Jupyter Notebook](https://img.shields.io/badge/jupyter-%23FA0F00.svg?style=for-the-badge&logo=jupyter&logoColor=white)](https://jupyter.org/)
[![Anaconda](https://img.shields.io/badge/Anaconda-%2344A833.svg?style=for-the-badge&logo=anaconda&logoColor=white)](https://www.anaconda.com)


![DALL·E 2024-01-04 18 07 52 - A futuristic digital art illustration depicting the concept of employee attrition prediction and analysis using machine learning models  The image fea](https://github.com/ViswanathRajuIndukuri/Employee-Attrition-Prediction/assets/144731305/582df905-9902-45ac-a06b-2704e6d8203d)
## Introduction

This project aims to predict employee attrition, which is a crucial concern for organizations. Employee attrition, or the rate at which employees leave a company, can have a significant impact on an organization's productivity, costs, and overall success. By predicting which employees are more likely to leave, companies can take proactive measures to retain their valuable talent.

In this analysis, we leverage a dataset with various features related to employees, such as job satisfaction, hourly rate, and environmental satisfaction, to build predictive models for employee attrition. The goal is to provide insights and predictions that can help organizations make informed decisions about employee retention strategies.

## Dataset

The dataset used for this project can be found [here](https://www.kaggle.com/code/yoojink/employee-attrition-analysis-eda-and-modeling/data). It includes information on employees' demographics, job roles, education levels, and more. Some of the important features include:

- Education
- Environment Satisfaction
- Job Involvement
- Job Satisfaction
- Performance Rating
- Relationship Satisfaction
- Work-Life Balance

## Data Preprocessing

To prepare the data for analysis, we performed the following steps:

- Removed unnecessary columns, such as 'EmployeeCount,' 'Over18,' 'StandardHours,' and 'EmployeeNumber.'
- Converted categorical features with string values into numerical representations using label encoding.

## Exploratory Data Analysis (EDA)

Conducted exploratory data analysis to gain insights into the dataset. Here are some key findings:

- Certain job roles, such as 'Laboratory Technician,' 'Sales Executive,' and 'Research Scientist,' are more likely to experience attrition.
- Employees with backgrounds in Life Sciences and Medical fields show higher attrition rates.
- Men tend to leave their jobs more frequently than women.
- Employees in the age bracket of 25-35 are more likely to leave their jobs.
- Single individuals have a higher attrition rate.

## Model Building and Evaluation

Built several machine learning models to predict employee attrition, including Ridge Regression, Logistic Regression, XGBoost, and Random Forest. The performance of these models was evaluated using accuracy scores, classification reports, and confusion matrices.

- The XGBoost model achieved the highest accuracy (88%) and performed well in terms of true positive and false positive rates.
