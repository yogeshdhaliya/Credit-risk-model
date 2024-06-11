# Credit-Risk-Model

This repository contains the code and notebooks used to build a credit risk prediction model for loan eligibility assessment.

Project Goals:
* Develop a model to predict loan approval category (P1-P4 representing risk levels) for new customers.
* Leverage the model to aid loan approval decisions.

Data:
• The dataset contains over 50,000 customer records with features including demographics, financial information, and loan history.
• The target variable is a categorical variable representing loan approval category (P1-P4).

Methodology:

1. Data Cleaning:
• Identified and addressed missing values using appropriate techniques.
• Handled data inconsistencies.
• Performed exploratory data analysis (EDA) to understand data distribution and relationships between features and the target variable.

2. Feature Engineering:
• Performed Chi-square tests to identify statistically significant relationships between categorical features and the target variable (reduced features by X%).
• Used Variance Inflation Factor (VIF) analysis to identify and remove highly correlated numerical features (reduced features by Y%).
• Implemented domain knowledge to create new features if necessary.

3. Model Building and Evaluation:
• Built a model (e.g., XGBoost) to predict loan approval category based on customer data.
• Performed hyperparameter tuning to optimize model performance.
• Evaluated model performance on unseen data using accuracy metrics.

Results:
• Achieved an accuracy rate of 85% on unseen data.
• Developed a model that can effectively assess credit risk and assist loan approval decisions.
Getting Started:

This repository includes:
• Jurpyter notebooks for data cleaning, feature engineering, model building, and evaluation.
