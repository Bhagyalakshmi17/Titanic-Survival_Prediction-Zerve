# Titanic Survival Prediction using Zerve

## Overview
This project demonstrates an end-to-end machine learning workflow using the Titanic dataset.  
The goal is to predict passenger survival using basic passenger information.

## Dataset
- Dataset: Titanic Dataset
- Source: Data Science Dojo public dataset, based on the Kaggle Titanic dataset
- Records: 891 passengers
- Target Variable: `Survived`

## Key Features Used
- `Pclass` - Passenger class
- `Age` - Passenger age
- `Fare` - Ticket fare

## Workflow
1. Loaded the Titanic dataset
2. Explored dataset structure and summary statistics
3. Checked and handled missing values
4. Visualized survival count, passenger class distribution, and age distribution
5. Trained a Logistic Regression classification model
6. Evaluated model performance using accuracy, confusion matrix, and classification report

## Model
- Algorithm: Logistic Regression
- Accuracy: Approximately 73.74%

## Key Insights
- Passenger class and fare are useful indicators of survival probability.
- Missing age values were handled using mean imputation.
- Logistic Regression provided a simple baseline model for binary classification.

## Technologies Used
- Python
- Pandas
- Matplotlib
- Scikit-learn
- Zerve

## How to Run
1. Open the notebook `Titanic_Survival_Prediction.ipynb`.
2. Run all cells from top to bottom.
3. The dataset loads directly from a public GitHub URL.
