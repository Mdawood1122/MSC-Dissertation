# Rice Dataset

## About

This notebook is for classifying rice grains into two types which are Jasmine and Gonen. I used morphological features of rice grains like area, perimeter, eccentricity and others to train the models.

The dataset has 18,185 samples in total with 9,985 Jasmine samples and 8,200 Gonen samples.

## Dataset

- **File:** rice_new.csv
- **Samples:** 18,185
- **Classes:** Jasmine and Gonen
- **Features:** 11 features (Area, MajorAxisLength, MinorAxisLength, Eccentricity, ConvexArea, EquivDiameter, Extent, Perimeter, Roundness, AspectRation, Class)
- **Split:** 70% training and 30% testing

## Models and Results

I first trained all three models with default settings to see the baseline accuracy.

| Model | Accuracy |
|-------|----------|
| Random Forest | 100% |
| SVM | 97.54% |
| KNN | 97.87% |

Then I applied three hyperparameter tuning methods on all three models:
- Bayesian Search
- Grid Search  
- Random Search

## CSV File Path

Make sure your CSV file is at this path in Google Drive:
```
/content/drive/MyDrive/rice_new.csv
```

## Key Observation

Random Forest got 100% accuracy on this dataset which shows the rice grain features are very good at separating the two classes. All three models performed well overall which means the dataset is well structured for classification.
