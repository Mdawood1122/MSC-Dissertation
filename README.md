# MSC Dissertation - How well-performing are default hyperparameters in Machine Learning libraries.

## About This Project

This is my MSC dissertation project where I compared how different hyperparameter tuning methods affect the performance of machine learning classifiers. I used three datasets and applied three classifiers on each one to see which tuning method works best.

The three classifiers I used are Random Forest, SVM and KNN. For tuning I used Bayesian Search, Grid Search and Random Search on all three models for each dataset.

## Author

**Muhammad Dawood**  
MSc Artificial Intelligence  
University of Stirling  
mdawood426@gmail.com

## Datasets Used

I worked on three datasets in this project:

1. **Rice Dataset** - classify rice grains as Jasmine or Gonen (binary classification)
2. **Churn Dataset** - predict if a customer will leave or stay (binary classification)  
3. **Mobile Price Dataset** - predict the price range of a mobile phone from 0 to 3 (multi-class classification)

## Results

### Rice Dataset (18,185 samples)
| Model | Accuracy |
|-------|----------|
| Random Forest | 100% |
| SVM | 97.54% |
| KNN | 97.87% |

### Churn Dataset (3,333 samples)
| Model | Default | Bayesian | Random Search | Grid Search |
|-------|---------|----------|---------------|-------------|
| RFC | 92.4% | 92.1% | 92.7% | 92.5% |
| SVM | 85.9% | 86.5% | 86.2% | 86.7% |
| KNN | 86.2% | 87.4% | 86.8% | 87.4% |

### Mobile Price Dataset (2,000 samples)
| Model | Default | Bayesian | Random Search | Grid Search |
|-------|---------|----------|---------------|-------------|
| RFC | 86.8% | 90.8% | 88.8% | 89.0% |
| SVM | 94.5% | 95.8% | 95.7% | 95.8% |
| KNN | 93.8% | 94.3% | 93.7% | 94.0% |

## Files

- `dissertation_rice_Dataset.ipynb` - rice dataset notebook
- `dissertation_churn_dataset.ipynb` - churn dataset notebook
- `dissertation_mobile_dataset.ipynb` - mobile price dataset notebook
- `README_rice.md` - rice dataset details
- `README_churn.md` - churn dataset details
- `README_mobile.md` - mobile dataset details

## How to Run the Notebooks

All notebooks are designed to run in Google Colab. You need to have the dataset CSV files saved in your Google Drive before running. Just open the notebook in Colab, mount your drive and run all cells.

> This project is part of my MSC dissertation at University of Stirling.
