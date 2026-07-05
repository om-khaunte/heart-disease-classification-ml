# Machine Learning for Early Heart Disease Risk Prediction in the Cleveland Dataset

This repository contains my self-directed research project on using machine learning to predict heart disease with the Cleveland subset of the UCI Heart Disease dataset. The project compares several standard models, including logistic regression, Random Forest, XGBoost, and SVM, and looks at how well they perform on a held-out test set.[1]

## What this project is

The goal of this project was to test whether a small set of routine clinical features could be used to build accurate heart disease prediction models on a well-known benchmark dataset.[1] I used the Cleveland subset, which includes 303 patients and 13 features such as age, chest pain type, blood pressure, cholesterol, exercise-induced angina, and ECG-related variables.[1]

## What I did

I cleaned the dataset, renamed the target label, one-hot encoded categorical variables, standardized numeric variables, and split the data into training, validation, and test sets using stratified sampling.[1] I started with logistic regression as a baseline, then trained Random Forest, XGBoost, and support vector machine models with hyperparameter tuning through randomized search and 5-fold cross-validation.[1]

## Main results

On the held-out test set, the tuned SVM reached an accuracy of 0.89 with an AUC of 0.91.[1] XGBoost reached an accuracy of 0.84 with an AUC of 0.96, and Random Forest reached an accuracy of 0.82 with an AUC of 0.93.[1] Feature importance analysis showed that exercise-induced angina, ST segment depression, age, and maximum heart rate were among the most important predictors.[1]

## Files

- `Machine Learning for Early Heart Disease Risk Prediction in the Cleveland Dataset.pdf` — final paper.[1]
- Figures included in the paper, such as the confusion matrix, ROC curves, and feature importance plot.[1]

## Why it matters

This project was meant to explore how far standard machine learning methods can go on a classic heart disease dataset while still staying interpretable.[1] It is not a clinical tool, but it does show how data-driven models can capture meaningful signals from routine patient variables.[1]

## Note

This is a self-published student research project.
