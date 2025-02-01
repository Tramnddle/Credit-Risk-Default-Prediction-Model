# Credit Risk Default Prediction Model

## Project Overview

This project focuses on the development of a classification model aimed at predicting loan defaulters and minimizing financial risk by assessing creditworthiness. By analyzing financial, demographic, and employment data of potential borrowers, the objective was to predict the likelihood of loan default and mitigate the risk of loss for lenders. The model aimed to uncover patterns in historical credit behavior and repayment trends, assisting in more informed loan approval decisions.

## Key Responsibilities

- **Data Collection & Preprocessing**  
  Processed a dataset of 143,727 borrowers, including attributes such as employment type, work experience, income, dependents, total loans, and payment history.

- **Feature Engineering**  
  Engineered new features, including:
    - Percentage of amount paid as interest in previous loans
    - Percentage of loans defaulted in the last two years  
  These features helped identify relevant predictors for loan default.

- **Exploratory Data Analysis (EDA)**  
  Performed univariate and bivariate analysis:
    - Numerical summaries (min, max, mean, median)
    - Categorical summaries (top, unique, count)
    - Correlation plots, box plots for feature insights

- **Modeling & Hyperparameter Optimization**  
  Developed a classification model using **LightGBM**, optimized hyperparameters using **Hyperopt** to improve model performance.

- **Model Explainability**  
  Used **SHAP** (Shapley Additive Explanations) for model explainability to interpret predictions and understand the impact of features on loan default outcomes.

- **Evaluation & Monitoring**  
  Evaluated model performance using:
    - ROC AUC
    - PR AUC
    - Score distributions and feature importance
  Continuously monitored the model to detect trends and anomalies, ensuring robustness and adaptability to changing customer data.

## Tech Stack

- **Languages**: Python
- **Libraries**: pandas, numpy, matplotlib, seaborn, scikit-learn, lightgbm, hyperopt, shap

## Outcome

The model effectively identified high-risk loan applicants and minimized financial loss for lenders. By accurately predicting defaulters and explaining decision-making, it contributed to more informed loan approval processes, enhancing profitability and reducing customer credit risk.
