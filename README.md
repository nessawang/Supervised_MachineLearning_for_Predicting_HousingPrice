# Supervised_MachineLearning_for_Predicting_HousingPrice

This repository contains two Jupyter notebooks that present different solutions to a housing price prediction problem.

### kaggle_simple_submission.ipynb

This notebook contains a basic solution for a Kaggle competition. Details of the exact model and feature engineering steps are not clearly mentioned in the notebook.

### ML_test_challenging.ipynb

This notebook presents a more complex solution to the housing price prediction problem. It includes the following steps:

1. Data Import and Preprocessing: This involves loading the data and preparing it for the machine learning models.
2. Feature Selection: Defining the feature vector (X) and target column (y).
3. Data Splitting: The data is split into a training set and a test set.
4. Model Building: Two different models, a Decision Tree and K-Nearest Neighbors (KNN), are built and tested. The process is iterated several times to fine-tune the model parameters.
5. Model Evaluation: The accuracy of the models is checked for each iteration.
6. Application to Validation Data: The final models are used to predict the housing prices in the validation data. The predicted prices are saved in a DataFrame and exported as a CSV file for further use.
