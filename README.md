# Feature Engineering & Preprocessing Pipeline

## Project Overview

This project demonstrates a robust and reusable machine learning preprocessing pipeline using Scikit-Learn.

The project uses the Default of Credit Card Clients dataset from the UCI Machine Learning Repository.

## Objectives

- Handle missing values
- Scale numerical features
- Encode categorical features
- Prevent data leakage
- Perform correlation analysis
- Perform feature importance analysis
- Build a reusable Scikit-Learn pipeline

## Dataset

Dataset:
Default of Credit Card Clients

Source:
UCI Machine Learning Repository

https://archive.ics.uci.edu/dataset/350/default

The dataset contains information about credit card clients and their payment behavior.

## Technologies

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-Learn
- Jupyter Notebook

## Machine Learning Workflow

Dataset
→ Train/Test Split
→ Numerical Preprocessing
→ Categorical Preprocessing
→ ColumnTransformer
→ Random Forest
→ Evaluation
→ Feature Importance

## Preprocessing

### Numerical Features

- Median imputation
- Standard scaling

### Categorical Features

- Most frequent imputation
- One-hot encoding

## Feature Analysis

Correlation analysis and Random Forest feature importance were performed to understand the contribution of different features.

## Project Structure

Credit-Card-Preprocessing-Pipeline/

├── data/

│   └── default of credit card clients.xls

├── notebooks/

│   └── feature_engineering_pipeline.ipynb

├── README.md

└── requirements.txt

## Author

Vinothini V