# Loan_Prediction

## Project Overview

Among all industries, insurance domain has the largest use of analytics & data science methods. This data set would provide you enough taste of working on data sets from insurance companies, what challenges are faced, what strategies are used, which variables influence the outcome etc.

## Problem Statement

The Company wants to automate the loan eligibility process (real time) based on customer detail provided while filling online application form. These details are Gender, Marital Status, Education, Number of Dependents, Income, Loan Amount, Credit History and others. To automate this process, they have given a problem to identify the customers segments, those are eligible for loan amount so that they can specifically target these customers. 

## Data Source

The dataset was obtained from [Kaggle Loan Prediction](https://www.kaggle.com/datasets/ninzaami/loan-predication/data). The data has 615 rows and 13 columns. This is a classification problem. 

## Data Used

- Data: The dataset was obtained from [Kaggle Loan Prediction](https://www.kaggle.com/datasets/ninzaami/loan-predication/data).
- Data Cleaning & Analysis: Python and Jupyter Notebook.
- Dependencies: Pandas, Numpy, sklearn-learn,Seaborn
- Model: Support Vector Machine (SVM)

## Summary of Findings

1. I observed missing values in the dataset. I handled it by dropping the rows that had missing values
2. I used label encoding to turn the output values(Loan Status) into 0's & 1's
3. Replaced the Dependency column value from 3+ to 4
4. Displayed the distribution of Education and Loan Status. Discovered people who graduated were more eligible to take loans than people who did not
5. Displayed the distribution of Marital Status and Loan Status. Discovered people who were married were more eligible to take loans than people single's
6. Displayed the distribution of Self Employed and Loan Status. Discovered people who were not self employed were more eligible to take loans than self employed
7. Converted categorical data to numerical
8. Split the data into Training and Testing model
9. Trained the model using Support Vector Machine(SVM)
10. Training data had accuracy score of 77%. Test had accuracy score of 81%


