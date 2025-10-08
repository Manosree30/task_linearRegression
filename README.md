# task_linearRegression
## Linear Regression Datasets Analysis
This repository contains a Jupyter Notebook performing basic and multivariate linear regression on diverse datasets, including study hours vs. score, house size vs. price, experience vs. salary, house price prediction with multiple features, and advertising spend vs. sales. The analysis employs Python data science libraries for exploratory analysis, model building, evaluation, and prediction.

## Contents
TASK.ipynb: Main notebook containing all analyses and code.

## Datasets Used
studyhoursscore.csv: Study hours and corresponding exam scores.

housesizeprice.csv: Size of houses (m²) and their prices.

salaryexperience.csv: Years of experience and corresponding salary.

housepricemulti.csv: House features (size, bedrooms) and price.

advertisingsales.csv: Advertising spend across TV, radio, social media, and resulting sales.

## Main Methods and Steps
Data Loading and Display: Uses pandas to load and preview datasets.

Preprocessing: Splitting datasets into training and test sets; managing features and targets.

Model Building: Fits linear regression models for single and multiple variables using scikit-learn.

Evaluation: Calculates metrics like RMSE (Root Mean Squared Error) and R² score for model performance.

Predictions: Example predictions on new data points for each model.

Outputs: Displays evaluation metrics, model coefficients, and predictions for easy interpretation.

## Technologies
Python 3.x

Jupyter Notebook

pandas, numpy

scikit-learn

## How to Run
Clone the repository.

Install dependencies:

pip install pandas numpy scikit-learn

Open and run TASK.ipynb in Jupyter Notebook or Google Colab.

## Notable Results
Linear relationships were identified and quantified for each domain dataset.

Regression equations and quality metrics (RMSE, R²) are shown in the notebook for educational comparison.