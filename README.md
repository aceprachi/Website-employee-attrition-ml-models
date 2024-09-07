# Employee Attrition Project

## Quick Introduction

In this project, the primary goal was to predict and analyze employee turnover to enhance hiring efficiency and ensure organizational stability. Through a detailed **Exploratory Data Analysis (EDA)**, I identified key drivers of employee attrition such as satisfaction levels, tenure, job role, and departmental impact. Leveraging machine learning models like **Random Forest**, **Logistic Regression**, and **K-Nearest Neighbors**, I achieved accurate predictions of employee turnover. This project provides crucial insights into the factors driving attrition and helps forecast future workforce needs.

## Key Features

- **Exploratory Data Analysis (EDA):**
  - **Key Observations:**
    - **Job Role and Department:** Certain roles and departments exhibited higher attrition rates, indicating a need for role-specific retention strategies.
    - **Satisfaction Levels:** Employees with lower satisfaction levels were more likely to leave, emphasizing the importance of workplace satisfaction programs.
    - **Tenure Impact:** Employees with short tenure were more prone to attrition, suggesting the need for focused onboarding and early engagement initiatives.
    - **Gender and Age:** Attrition rates varied across different gender and age groups, showing potential demographic-specific trends.

- **Data Transformation:** 
  - Used **Label Encoding** to convert categorical features such as `Department`, `Job Role`, and `Education Field` into numerical format for machine learning compatibility.

## Models Used

1. **Logistic Regression:**
   - **Overview:** A simple and effective model for binary classification tasks, well-suited for predicting employee attrition.
   - **Performance:** Achieved high accuracy on training data (93.33%) and test data (96.00%). It provides a solid baseline model for predicting whether an employee will leave or stay based on key factors.

2. **K-Nearest Neighbors (KNN):**
   - **Overview:** A non-parametric algorithm that works by finding the nearest data points (neighbors) to classify a new point. It is effective when the data structure allows for meaningful comparisons between examples.
   - **Performance:** Similar accuracy to Logistic Regression, performing consistently well on both training (93.33%) and test data (96.00%). It adapts well to new data but can be sensitive to noise or outliers.

3. **Random Forest Classifier:**
   - **Overview:** A powerful ensemble learning method that builds multiple decision trees and merges them to get a more accurate and stable prediction.
   - **Performance:** The model delivered perfect accuracy on training data (100%) but slightly lower accuracy on test data (84.00%). This indicates strong performance with familiar data but some variability when dealing with unseen data.
