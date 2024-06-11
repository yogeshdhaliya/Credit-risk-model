# Credit Risk Prediction Model for Loan Eligibility Assessment

## Project Goals

- Develop a model to predict loan approval category (P1-P4 representing risk levels) for new customers.
- Leverage the model to aid loan approval decisions.

## Data

- Over 50,000 customer records with features including demographics, financial information, and loan history.
- Target variable: Categorical variable representing loan approval category (P1-P4).

## Methodology

### Data Cleaning
- Identified and addressed missing values using appropriate techniques.
- Handled data inconsistencies.
- Performed exploratory data analysis (EDA) to understand data distribution and relationships.

### Feature Engineering
- Conducted Chi-square tests to identify significant relationships between categorical features and the target variable.
- Used VIF analysis to remove highly correlated numerical features.
- Implemented domain knowledge to create new features if necessary.

### Model Building and Evaluation
- Built an XGBoost model to predict loan approval category.
- Tuned hyperparameters to optimize model performance.
- Evaluated model on unseen data using accuracy metrics.

## Results

- Achieved 85% accuracy on unseen data.
- Developed a model effective in assessing credit risk and aiding loan approval decisions.

## Getting Started

This repository includes:
- Jupyter notebooks for data cleaning, feature engineering, model building, and evaluation.
