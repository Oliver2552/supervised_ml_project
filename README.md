# Diabetes Prediction Project

## Overview

This project aims to predict whether an individual has diabetes (or not) based on several health-related predictors. The dataset used for this analysis contains information such as glucose levels, BMI, age, pregnancies, hereditary caclulations
and a few other variables.

## Table of Contents

- [Dataset]
- [Exploratory Data Analysis (EDA)]
- [Data Preprocessing]
- [Model Training]
- [Evaluation Metrics]
- [Results]
- [Usage]

## Dataset

The dataset used in this project is the [Diabetes Dataset] sourced from: https://www.kaggle.com/datasets/akshaydattatraykhare/diabetes-dataset.

## Exploratory Data Analysis (EDA)

- Inidial EDA of the dataset to understand its columns, structure, presence of missing values, and relationships between each other and with outcome variable.
- Plotted the distribution of predictors and their correlation with the outcome variable.

## Data Preprocessing

Performed several preprocessing steps, including:

- Checking for missing values.
- Identifying and handling outliers, replacing values on 1% extremes with ones closer to mean.
- Scaling/normalizating of predictors
- Dealing with imbalanced data with oversampling of minority class.

## Model Training and Evaluation

Trained/evaluated two models:

1. Logistic Regression (base model)
2. Random Forest (Ensemble)

### Evaluation Metrics

- Accuracy
- Precision
- Recall
- F1 Score
- ROC-AUC
- 5-fold Cross Validation
- Confusion Matrix


## Results

Results indicated overall better performance from the Random Forest Ensemble approach - it performed better on 5 different subsets of the dataset and overall struck a better balance between accuracy and precision as opposed to 
the base model Logistic Regression. 

That being said, the Logistic Regression did better in recall, correctly identitying positive cases.

## Usage

1. Clone the repository:

   git clone https://github.com/your-username/diabetes-prediction.git

2. Ensure you have all modules installed (as seen in the .ipynb file)

3. Ensure dataset (diabetes.csv) is in the same working directory.
