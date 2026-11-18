Titanic Survival Prediction

Overview

A machine learning project based on the Kaggle Titanic competition. The goal is to predict whether a passenger survived the Titanic disaster using passenger attributes and a Random Forest classifier.

Project Objectives

* Explore survival patterns in the training dataset.
* Compare survival rates between female and male passengers.
* Build a baseline classification model.
* Generate survival predictions for the test dataset in Kaggle submission format.

Methods

1. Data Exploration

* Load the training and test datasets using Pandas.
* Examine the dataset structure and passenger features.
* Calculate survival rates for female and male passengers.

2. Feature Engineering

The model uses the following features:

* Pclass — Passenger class
* Sex — Passenger sex
* SibSp — Number of siblings and spouses aboard
* Parch — Number of parents and children aboard

Categorical features are encoded using Pandas get_dummies().

3. Model Training

A Random Forest classifier from Scikit-learn is trained on the labeled training data.

Model configuration:

* Number of trees: 100
* Maximum tree depth: 5
* Random state: 1

4. Prediction and Submission

The trained model generates survival predictions for the test dataset. The predictions are exported to submission.csv in the format required by the Kaggle competition.

Technologies

* Python
* Pandas
* NumPy
* Scikit-learn
* Jupyter Notebook

How to Run

Install dependencies

python -m pip install pandas numpy scikit-learn

Run the notebook

Open the notebook in Jupyter Notebook or VS Code and run the cells in order.

The Kaggle Titanic dataset must be available at the expected input paths.

Future Improvements

* Handle missing values systematically.
* Improve feature engineering.
* Compare Random Forest with other classification models.
* Evaluate performance using cross-validation.
* Tune hyperparameters and analyze model performance.

Learning Outcomes

This project explores basic data analysis, categorical feature encoding, supervised classification, and the process of generating predictions for a machine learning competition.
