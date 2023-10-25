# Tutorial Modelling Data Titanic

Tutorial ini akan mengubah data titanic menjadi data yang siap untuk dilakukan pemodelan.

## Prerequisites
1. Download data [here](https://www.kaggle.com/datasets/fossouodonald/titaniccsv)
2. Instalasi dengan `pip install requirements.txt`

## Getting Started
- Dataset splitting
- Training
- Model validation

### Dataset Splitting

Split data into training, validation and test set


```code
x_train, y_train, x_test, y_test = dataset_splitting()
x_train.shape, y_train.shape
```

## References
- scikit-learn documentations