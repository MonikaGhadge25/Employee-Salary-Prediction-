# Employee Salary Prediction

This project predicts whether a person's income is above $50K or not, 
based on details like age, education, occupation, and hours worked per week.

## Dataset
UCI Adult Census Income dataset (48,842 records, 15 columns).

## What I did
- Cleaned the data: fixed missing values, removed outliers, dropped extra columns
- Converted text columns to numbers and scaled the data
- Trained 5 models: Logistic Regression, Random Forest, KNN, SVM, Gradient Boosting
- Compared their accuracy and saved the best model

## Result
Gradient Boosting performed best with 85.73% accuracy.

## Tools Used
Python, Pandas, NumPy, Scikit-learn, Matplotlib, Jupyter Notebook

## How to Run
Open Employee_Salary_Prediction.ipynb in Jupyter Notebook or Google Colab and run all cells.
