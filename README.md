# Notebook Learning: SciKitLearn Tutorials

This repository contains notebooks demonstrating various preprocessing techniques and machine learning algorithms using scikit-learn.

## Requirements & Installation

To run these notebooks, clone the repository and install the dependencies listed in `requirements.txt`:

```bash
pip install -r requirements.txt
```

## Notebooks

- `001_Test_Train_Split.ipynb`: Demonstrates how to split a dataset into training and testing sets to evaluate model performance on unseen data.
- `002_Scaling.ipynb`: Demonstrates feature scaling using `StandardScaler` (standardizing) and `MinMaxScaler` (normalizing to a range).
- `003_One_Hot_Encoder.ipynb`: Demonstrates one-hot encoding for categorical variables with no inherent order.
- `004_Ordinal_Encoder.ipynb`: Demonstrates ordinal encoding for categorical variables with an inherent order.
- `005_Simple_Imputer.ipynb`: Demonstrates imputation strategies for handling missing values in a dataset.
- `006_Decision_Tree.ipynb`: Demonstrates training and evaluating a Decision Tree classifier, which splits data based on feature values to make predictions.
- `007_Random_Forest.ipynb`: Demonstrates training a Random Forest ensemble model, which combines multiple decision trees to improve accuracy and robustness.
- `008_Linear_Regression.ipynb`: Demonstrates linear regression for predicting continuous values by finding the best-fit line through the data.
- `009_Logistic_Regression.ipynb`: Demonstrates logistic regression for binary classification, modeling the probability of an outcome.
- `010_K_Nearest_Neighbours.ipynb`: Demonstrates the K-Nearest Neighbours algorithm, which classifies data points based on the majority class of their nearest neighbors.
- `011_Cross_Validation.ipynb`: Demonstrates cross-validation techniques for robustly evaluating model performance and tuning hyperparameters.
