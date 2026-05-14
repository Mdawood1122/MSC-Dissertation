# Mobile Price Dataset

## About

This notebook is for predicting the price range of a mobile phone. Unlike the other two datasets this is a multi-class classification problem with four price ranges (0, 1, 2, 3) where 0 is low cost and 3 is very high cost.

The dataset has features like battery power, RAM, camera specs, screen size and other mobile phone specifications.

## Dataset

- **File:** train.csv
- **Samples:** 2,000
- **Classes:** 4 price ranges (0 = low, 1 = medium, 2 = high, 3 = very high)
- **Split:** 70% training and 30% testing

## Models and Results

Default accuracy for all three models:

| Model | Accuracy |
|-------|----------|
| Random Forest | 86.8% |
| SVM | 94.5% |
| KNN | 93.8% |

Results after hyperparameter tuning:

| Model | Bayesian | Random Search | Grid Search |
|-------|----------|---------------|-------------|
| RFC | 90.8% | 88.8% | 89.0% |
| SVM | 95.8% | 95.7% | 95.8% |
| KNN | 94.3% | 93.7% | 94.0% |

Best accuracy was **95.8%** achieved by SVM with Bayesian Search and Grid Search.

## CSV File Path

Make sure your CSV file is at this path in Google Drive:
```
/content/drive/MyDrive/mobile_price/train/train.csv
```

## Key Observation

SVM performed the best on this dataset. One interesting thing is that Random Forest improved a lot with tuning, going from 86.8% to 90.8% with Bayesian Search which is a 4% improvement. This shows that RFC benefits more from tuning on this dataset compared to SVM and KNN which were already performing well at default settings.
