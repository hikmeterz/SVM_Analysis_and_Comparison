﻿# SVM_Analysis_and_Comparison


## Project Description
This repository contains the implementation and analysis of Support Vector Machine (SVM) and its comparison with other machine learning algorithms. The project includes data preprocessing, model training, and evaluation using a dataset. The project aims to observe the performance of SVM and other models in terms of accuracy and training time.

## Files
- `161101071.html`: HTML report of the analysis.
- `161101071.ipynb`: Jupyter notebook containing the code and analysis.
- `161101071.pdf`: PDF report of the analysis.
- `161101071_test.ipynb`: Jupyter notebook for testing the model.
- `model.pkl`: Pickle file of the trained model.
- `preprocessing.pkl`: Pickle file of the preprocessing steps.
- `requirements.txt`: Required Python packages.

## Data Preprocessing
In the data preprocessing part, non-numeric features were converted to numeric. Recurring features were extracted, and the data was cleaned and prepared for model training.

## Model Training and Evaluation
The models were trained and evaluated based on their accuracy and training time. The SVM model, Logistic Regression, and other algorithms were compared. It was observed that:
- The training time of SVM was significantly longer than others.
- Without applying cross-validation (CV), the SVM model did not perform well.
- Logistic Regression provided better accuracy compared to SVM.
- Retraining the top 5 features reduced the training time but slightly decreased the accuracy.

## Requirements
Ensure you have the required Python libraries installed:
- `numpy`
- `pandas`
- `scikit-learn`
- `matplotlib`
- `seaborn`
