# Credit Card Preprocessing Pipeline

## Project Overview

A reusable and leak-free machine learning preprocessing pipeline developed using Scikit-Learn.

The project demonstrates data preprocessing, feature engineering, model training, correlation analysis, and feature importance analysis using a structured machine learning workflow.

## Objectives

- Handle missing values
- Scale numerical features
- Encode categorical features
- Prevent data leakage
- Transform features using ColumnTransformer
- Train a Random Forest classifier
- Perform correlation analysis
- Analyze feature importance
- Build a reusable preprocessing pipeline

## Dataset

This project uses the Default of Credit Card Clients dataset.

Dataset Source:

https://archive.ics.uci.edu/dataset/350/default

## Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-Learn
- Jupyter Notebook

## Machine Learning Workflow

Dataset  
↓  
Train-Test Split  
↓  
Missing Value Imputation  
↓  
Numerical Scaling  
↓  
Categorical Encoding  
↓  
ColumnTransformer  
↓  
Random Forest  
↓  
Model Evaluation  
↓  
Correlation Analysis  
↓  
Feature Importance

## Preprocessing

### Numerical Features

- Missing values are handled using median imputation.
- Numerical features are scaled using StandardScaler.

### Categorical Features

- Missing values are handled using the most frequent value.
- Categorical features are converted using One-Hot Encoding.

## Data Leakage Prevention

The dataset is divided into training and testing sets before fitting preprocessing transformations. This helps prevent information from the test dataset from being used during training.

## Results

The original training dataset contained:

- 24,000 rows
- 24 features

After preprocessing, the training data contained:

- 24,000 rows
- 34 transformed features

The increase in features is due to One-Hot Encoding of categorical variables.

## Project Structure

```text
Credit-Card-Preprocessing-Pipeline/
│
├── data/
│
├── notebooks/
│   └── feature_engineering_pipeline.ipynb
│
├── README.md
├── requirements.txt
└── .gitignore