# Heart Disease Prediction (PRCP-1016)

Machine learning classification project to predict heart disease presence using patient health data.

## Dataset
- 180 patient records
- Features: values.csv (14 columns) merged with labels.csv on patient_id
- Target: heart_disease_present (100 No / 80 Yes)

## Approach
- Data preprocessing and exploratory data analysis
- Compared 6 classification models: Logistic Regression, KNN, Decision Tree, Random Forest, Gradient Boosting, SVM
- Model selection via 5-fold cross-validation
- Hyperparameter tuning using GridSearchCV

## Results
- Best model: Logistic Regression
- Test ROC-AUC: 0.934

## Tech Stack
Python, Pandas, NumPy, Scikit-learn, Jupyter Notebook

## Files
- `PRCP-1016-HeartDieseasePred_Final_Submission.ipynb` — main notebook
- `values.xls`, `labels.xls` — dataset files
