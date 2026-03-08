# Employee Classification

A machine learning project that predicts employee outcomes using demographic and professional features. The notebook compares multiple classification models and evaluates their performance.

## Overview
The project includes:
- Data preprocessing and feature encoding
- Feature scaling
- Training multiple classification models
- Hyperparameter tuning
- Model evaluation and comparison

## Models Used
- Logistic Regression
- Support Vector Machine (SVM)
- K-Nearest Neighbors (KNN)

## Tech Stack
- Python
- Pandas
- NumPy
- Scikit-learn
- Plotly
- Jupyter Notebook

## Dataset Features
- Education
- JoiningYear
- City
- PaymentTier
- Age
- Gender
- EverBenched
- ExperienceInCurrentDomain

## Workflow
1. Load and explore the dataset
2. Preprocess data (encoding + scaling)
3. Split data into train and test sets
4. Train classification models
5. Tune hyperparameters using GridSearchCV
6. Evaluate models using accuracy, precision, recall, and F1-score

## Run the Project

```bash
pip install pandas numpy scikit-learn plotly
jupyter notebook employee_classification.ipynb
```

## Results
Support Vector Machine achieved the best overall performance compared to Logistic Regression and KNN.
