# Intelligent Loan Approval System

## Project Overview

This project implements an **intelligent loan approval system** using Machine Learning to predict whether a loan application should be **Approved** or **Rejected**, helping the bank make **faster, unbiased, and accurate decisions**.

---

## Dataset
The dataset consists of historical loan applications with features such as:

- Applicant income
- Employment details
- Credit history
- Property details
- Other demographic and financial information  

---

## Steps Performed

1. **Exploratory Data Analysis (EDA)**  
   - Checked data distribution  
   - Identified missing values  
   - Visualized feature relationships  

2. **Feature Engineering & Encoding**  
   - Converted categorical variables into numeric using encoding techniques  
   - Created new features to improve model performance  

3. **Correlation Analysis**  
   - Generated a correlation heatmap to identify relationships between features  

4. **Feature Scaling**  
   - Standardized numerical features for algorithms sensitive to scale (e.g., kNN, Logistic Regression)  

5. **Model Training & Evaluation**  
   - Trained **Logistic Regression**, **k-Nearest Neighbors (kNN)**, and **Naive Bayes** classifiers  
   - Evaluated models using precision, recall, and accuracy  
   - Naive Bayes emerged as the best-performing model based on **precision**  

---

## Technologies & Libraries Used
- Python 3.x  
- pandas, numpy  
- scikit-learn  
- matplotlib, seaborn  

---
