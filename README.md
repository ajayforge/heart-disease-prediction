# Heart Disease Prediction (PRCP-1016)

Machine learning classification project to predict the presence of heart disease using patient health data.

## Project Overview

Built an end-to-end classification pipeline covering data preparation, exploratory data analysis, model comparison, cross-validation, hyperparameter tuning, and final model evaluation.

## Dataset

- 180 patient records
- 14 clinical features
- Target: `heart_disease_present`
- Class distribution: 100 No / 80 Yes
- Input data: `values.csv` merged with `labels.csv` using `patient_id`

## Workflow

1. Data preparation and merging
2. Data preprocessing
3. Exploratory Data Analysis (EDA)
4. Train-test split
5. Classification model comparison
6. 5-fold cross-validation
7. Hyperparameter tuning with `GridSearchCV`
8. Final model evaluation

## Models Compared

- Logistic Regression
- K-Nearest Neighbors (KNN)
- Decision Tree
- Random Forest
- Gradient Boosting
- Support Vector Machine (SVM)

## Results

**Best Model:** Logistic Regression

| Metric | Test Result |
|---|---:|
| ROC-AUC | 0.934 |

The selected model demonstrated strong discriminative performance on the test set.

## Key Takeaways

- Compared six different classification algorithms using a consistent evaluation workflow.
- Used 5-fold cross-validation for model selection.
- Applied `GridSearchCV` to optimize model hyperparameters.
- Selected Logistic Regression based on model evaluation results.

## Tech Stack

Python · Pandas · NumPy · Scikit-learn · Jupyter Notebook

## Files

- `PRCP-1016-HeartDieseasePred_Final_Submission.ipynb` — Complete project notebook
- `values.xls` — Patient feature data
- `labels.xls` — Target labels
