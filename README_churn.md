# Churn Dataset

## About

This notebook is for predicting customer churn. The goal is to classify whether a customer will leave the service (churn = yes) or stay (churn = no). This is a binary classification problem.

The dataset contains customer data from a telecom company with 3,333 records.

## Dataset

- **File:** churn_t.csv
- **Samples:** 3,333
- **Classes:** Churn Yes / Churn No
- **Split:** 70% training and 30% testing

## Models and Results

Default accuracy for all three models:

| Model | Accuracy |
|-------|----------|
| Random Forest | 92.4% |
| SVM | 85.9% |
| KNN | 86.2% |

Results after hyperparameter tuning:

| Model | Bayesian | Random Search | Grid Search |
|-------|----------|---------------|-------------|
| RFC | 92.1% | 92.7% | 92.5% |
| SVM | 86.5% | 86.2% | 86.7% |
| KNN | 87.4% | 86.8% | 87.4% |

Best accuracy was **92.7%** achieved by Random Forest with Random Search.

## CSV File Path

Make sure your CSV file is at this path in Google Drive:
```
/content/drive/MyDrive/churn_t.csv
```

## Key Observation

Random Forest performed the best on this dataset. Hyperparameter tuning helped improve the results slightly for all models. KNN improved from 86.2% to 87.4% with both Bayesian and Grid Search which is a noticeable improvement.
