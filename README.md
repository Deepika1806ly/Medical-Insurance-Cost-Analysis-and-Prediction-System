# Medical Insurance Cost Analysis and Prediction System

## Project Overview

This project analyzes medical insurance data and predicts insurance charges using Machine Learning algorithms. 
It performs data preprocessing, visualization, regression analysis, and classification to understand the factors affecting insurance costs.

## Objectives

*  Analyze insurance customer data.
*  Identify factors influencing insurance charges.
*  Visualize important relationships in the dataset.
*  Predict insurance costs using Linear Regression.
*  Classify insurance categories using Logistic Regression.

## Technologies Used

*  Python
*  Pandas
*  NumPy
*  Matplotlib
*  Seaborn
*  Scikit-learn
*  Dataset Features
*  Age
*  Sex
*  BMI (Body Mass Index)
*  Children
*  Smoker Status
*  Region
*  Insurance Charges

## Project Workflow

### 1. Data Preprocessing

Load dataset.
Check missing values.
Remove duplicate records.
Encode categorical variables using Label Encoding.

### 2. Exploratory Data Analysis (EDA)
Age Distribution
-<img width="697" height="452" alt="Screenshot 2026-06-17 115342" src="https://github.com/user-attachments/assets/ad02c771-3655-4f69-a462-876d679b18a8" />

BMI Distribution
-<img width="695" height="443" alt="Screenshot 2026-06-17 115401" src="https://github.com/user-attachments/assets/d9629eb1-edc1-4977-a149-a70d011b005b" />

Insurance Charges Distribution
-<img width="710" height="462" alt="Screenshot 2026-06-17 115434" src="https://github.com/user-attachments/assets/5fc58944-3cb7-444d-8fa5-b8a0ddb28287" />

Age vs Charges
<img width="717" height="482" alt="Screenshot 2026-06-17 115501" src="https://github.com/user-attachments/assets/445b2844-0cfd-4d4f-84be-19e0077ad74c" />

BMI vs Charges
<img width="717" height="471" alt="Screenshot 2026-06-17 115524" src="https://github.com/user-attachments/assets/d840026e-12d6-430c-b4f3-a5de1bff39f6" />

Smoker vs Charges
<img width="721" height="467" alt="Screenshot 2026-06-17 115545" src="https://github.com/user-attachments/assets/edc617c4-a736-4782-a3d4-1b7de489350a" />

Region-wise Charges
<img width="712" height="463" alt="Screenshot 2026-06-17 115613" src="https://github.com/user-attachments/assets/900b8ebe-22bb-4f16-93e8-a6d84ef6c35d" />

Correlation Heatmap
<img width="647" height="445" alt="Screenshot 2026-06-17 115629" src="https://github.com/user-attachments/assets/5c9c89a5-bb14-4635-9e42-45aa5addf13f" />

### 3. Regression Models
Simple Linear Regression
Feature: Age
Target: Insurance Charges
Evaluation Metric: R² Score
Multiple Linear Regression
Features:
Age
BMI
Children
Smoker
Target: Insurance Charges
Evaluation Metric: R² Score

### 4. Classification Model
Logistic Regression
Creates an Insurance Category based on median charges.
Predicts whether a customer's insurance cost is High or Low.

## Evaluation Metrics:

*  Accuracy Score
*  Confusion Matrix
*  Expected Output
*  Statistical summary of the dataset.
*  Visual representations of key patterns.
*  Insurance charge predictions.
*  Insurance category classification results.
*  Model performance metrics.

## Conclusion

This project demonstrates how Machine Learning techniques can be used to analyze medical insurance data, predict insurance charges, and classify customers based on their insurance costs. The results help understand the impact of factors such as age, BMI, smoking habits, and family size on insurance expenses.
