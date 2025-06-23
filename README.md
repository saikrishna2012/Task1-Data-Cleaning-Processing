# Task 1: Data Cleaning & Preprocessing – Titanic Dataset

## Objective
The goal of this task is to clean and preprocess the Titanic dataset for machine learning purposes.
This includes handling missing data, encoding categorical features, scaling numerical features, and removing outliers.

## Dataset
- Source: [Kaggle – Titanic Dataset](https://www.kaggle.com/datasets/yasserh/titanic-dataset)

## Tools Used
- Python
- Pandas
- NumPy
- Seaborn
- Matplotlib
- Scikit-learn

## What Was Done
- Loaded the dataset from a public URL
- Dropped irrelevant columns (like Name, Ticket, Cabin)
- Filled missing values in Age and Embarked
- Converted categorical values (Sex, Embarked) into numeric format
- Scaled Age and Fare features using StandardScaler
- Detected and removed outliers using IQR method
- Saved the cleaned data to a CSV file

## Output
- "cleaned_titanic.csv" – cleaned and ready for analysis/modeling

