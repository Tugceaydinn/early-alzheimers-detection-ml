# Early Alzheimer’s Disease Detection Using Machine Learning

This project explores the use of machine learning models for the early classification of Alzheimer’s disease using handwriting/drawing-based clinical features.

## Project Overview

Alzheimer’s disease is a progressive neurodegenerative disorder where early detection can support timely clinical assessment and intervention. In this project, I developed and compared several machine learning models to classify participants based on extracted digital handwriting and drawing features.

## Dataset

The dataset contains 174 observations and 452 columns, including movement, timing, pressure, speed, and pen-position related features. The target variable is `class`, representing the diagnostic category.

Due to data privacy and licensing limitations, the original dataset is not included in this repository. The notebook is structured to demonstrate the modelling workflow.

## Methods

The workflow includes:

- Exploratory data analysis
- Data cleaning and feature inspection
- Train-test split
- Feature standardisation
- Machine learning model comparison
- Hyperparameter optimisation
- Model performance evaluation

Models tested:

- Random Forest
- Gradient Boosting
- Logistic Regression

## Results

The best performing baseline model was Logistic Regression, achieving approximately 94% test accuracy on the selected split. Tree-based models also achieved approximately 89% accuracy.

Because the dataset is small and high-dimensional, future work should include stratified cross-validation, feature selection, and external validation.

## Tech Stack

- Python
- pandas
- scikit-learn
- matplotlib
- seaborn
- Optuna
- Jupyter Notebook

## Future Improvements

- Add cross-validation and F1-score based evaluation
- Add confusion matrix and ROC-AUC analysis
- Apply feature selection or dimensionality reduction
- Refactor notebook into reusable Python scripts
- Add a reproducible environment file
- Improve model interpretability using feature importance or SHAP

## Author

Tuğçe Aydın  
MSc Data & Computational Science, University College Dublin
