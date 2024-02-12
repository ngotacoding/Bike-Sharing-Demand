# Predict Bike Sharing Demand with AutoGluon

This is the first project in the AWS Machine Learning Fundamentals Nanodegree by Udacity

## Project Overview
In this project, I applied the knowledge and methods learned in the Introduction to Machine Learning course to compete in a Kaggle competition using the AutoGluon library. The objective is to predict bike sharing demand by training a model with the Bike Sharing Demand dataset and submitting predictions to Kaggle for ranking. I iterated on the process by adding features to the dataset and tuning hyperparameters to improve my score. 

## Dataset

The dataset used is the Bike Sharing Demand dataset from the [Kaggle Bike Sharing Demand Competition](https://www.kaggle.com/c/bike-sharing-demand/overview). 

## Dependencies
- Python 3.7
- MXNet 1.8
- Pandas >= 1.2.4
- AutoGluon 0.2.0

Install with **pip**


## Repository Structure
```
Bike Sharing Demand/
├── LICENSE.txt                           # License file
├── project_notebook.html                 # HTML export of the project notebook
├── project_notebook.ipynb                # Project jupyter notebook
├── project_report.md                     # Markdown file of the project report
├── README.md                             # Readme file for the project repository
├── sampleSubmission.csv                  # Sample submission file
├── submission.csv                        # CSV file for initial submission
├── submission_new_features.csv           # CSV file for submission with new features
├── submission_new_hpo.csv                # CSV file for submission after hyperparameter tuning
├── submission_new_hpo2.csv               # Additional CSV file for submission after hyperparameter tuning
├── submission_new_hpo3.csv               # Additional CSV file for submission after hyperparameter tuning
├── submission_new_hpo4.csv               # Additional CSV file for submission after hyperparameter tuning
├── test.csv                              # Test dataset
└── train.csv                             # Train dataset
```
