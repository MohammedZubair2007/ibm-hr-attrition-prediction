# IBM HR Analytics — Employee Attrition Prediction

## Project Overview

This machine learning project explores employee attrition and develops classification models to predict whether an employee is likely to leave an organization, using the IBM HR Analytics Employee Attrition dataset.

The project follows a typical machine learning workflow, from exploratory data analysis and preprocessing to model training, evaluation, cross-validation, and classification threshold tuning.

## Business Problem

Employee attrition can increase recruitment costs, disrupt teams, and result in the loss of experienced employees. Understanding patterns associated with attrition can help organizations investigate retention challenges and develop evidence-informed strategies.

## Objectives

- Explore employee characteristics and attrition patterns.
- Clean and preprocess numerical and categorical features.
- Build and compare multiple classification models.
- Evaluate performance using precision, recall, F1-score, and ROC-AUC.
- Apply cross-validation and experiment with classification thresholds.
- Interpret model results and discuss limitations.

## Technologies Used

- Python
- Pandas and NumPy
- Matplotlib and Seaborn
- Scikit-learn
- XGBoost
- Google Colab and Jupyter Notebook

## Machine Learning Models

1. Logistic Regression
2. Random Forest Classifier
3. XGBoost Classifier

## Evaluation

The models were compared using accuracy, precision, recall, F1-score, ROC-AUC, and confusion matrices.

Because the dataset contains substantially more employees who stayed than employees who left, accuracy alone is not sufficient to assess performance. Recall and F1-score for the attrition class are also important.

A classification threshold was tuned for Logistic Regression using out-of-fold predictions generated from the training data.

<img width="1312" height="742" alt="image" src="https://github.com/user-attachments/assets/d894993b-7228-4d30-bfa5-88ecd1b77b51" />


## Key Learning Outcomes

- Exploratory data analysis and feature preparation
- Encoding categorical features and scaling numerical features
- Building machine learning pipelines
- Comparing classification algorithms
- Evaluating imbalanced classification problems
- Cross-validation and classification threshold tuning
- Interpreting model coefficients and communicating limitations

## Repository Contents

- `Employee_Attrition_ML_Project.ipynb` — notebook containing the analysis, preprocessing, model training, and evaluation.

## Limitations

- Model performance depends on the dataset and may not generalize to other organizations.
- Model associations do not establish the causes of employee attrition.
- The evaluation results are exploratory; the test set was consulted during model comparison and should not be treated as a completely untouched final evaluation.
- The model should not be used as the sole basis for decisions about individual employees. Any real-world application would require additional validation, fairness assessment, privacy safeguards, and human oversight.

## Future Improvements

- Perform further hyperparameter tuning.
- Evaluate additional classification and imbalance-handling techniques.
- Assess fairness and performance across relevant employee groups.
- Validate the model on independent data.
- Develop an interactive demonstration for educational purposes.

## Disclaimer

This is an educational portfolio project. Its predictions are not intended to determine employment outcomes or replace human judgment.




