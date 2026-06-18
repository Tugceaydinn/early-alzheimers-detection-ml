# Early Alzheimer’s Disease Detection Using Handwriting Analysis

This project explores the use of machine learning models for the early classification of Alzheimer’s disease using handwriting and drawing-based clinical features.

## Project Overview

Alzheimer’s disease is a progressive neurodegenerative disorder where early detection can support timely clinical assessment and intervention. In this project, I developed and compared several machine learning models to classify participants based on extracted digital handwriting and drawing features.

## Dataset

This project uses the publicly available **Handwriting Data to Detect Alzheimer's Disease** dataset from Kaggle.

Dataset source:  
https://www.kaggle.com/datasets/taeefnajib/handwriting-data-to-detect-alzheimers-disease

The dataset is licensed under the **Creative Commons Attribution 4.0 International (CC BY 4.0)** license. Under this license, the dataset can be shared and adapted, provided that appropriate credit is given to the original source.

The dataset contains handwriting and drawing-based features used for Alzheimer's disease classification.

To reproduce the analysis, download the dataset from Kaggle and place the CSV file in:

```text
data/data.csv
```

Dataset attribution:  
Taef Najib, *Handwriting Data to Detect Alzheimer's Disease*, Kaggle, CC BY 4.0.

## Methods

The workflow includes:

- Exploratory data analysis
- Data cleaning and feature inspection
- Train-test split
- Feature standardisation
- Machine learning model comparison
- Hyperparameter optimisation
- Model performance evaluation

## Models Tested

- Random Forest
- Gradient Boosting
- Logistic Regression

## Results

The best performing baseline model was Logistic Regression, achieving approximately 94% test accuracy on the selected train-test split. Tree-based models also achieved approximately 89% accuracy.

Because the dataset is small and high-dimensional, future work should include stratified cross-validation, feature selection, and external validation. Therefore, the results should be interpreted as an exploratory machine learning analysis rather than a clinically validated diagnostic tool.

## Tech Stack

- Python
- pandas
- scikit-learn
- matplotlib
- seaborn
- Optuna
- Jupyter Notebook

## Future Improvements

- Add stratified cross-validation and F1-score based evaluation
- Add confusion matrix and ROC-AUC analysis
- Apply feature selection or dimensionality reduction
- Refactor notebook into reusable Python scripts
- Add a reproducible environment file
- Improve model interpretability using feature importance or SHAP

## Author

Tuğçe Aydın  
MSc Data & Computational Science  
University College Dublin
