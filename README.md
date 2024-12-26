# Credit-Card-Fraud-Detection
This repository contains the implementation of a Credit Card Fraud Detection system, where the goal is to detect fraudulent transactions using machine learning algorithms. The model is trained on a dataset containing credit card transactions and classifies them as either fraudulent or legitimate.

##  Table of Contents

Overview

Dataset

Installation

Usage

Models and Techniques

Evaluation Metrics

Contributing

License

Acknowledgments


## Overview

Credit card fraud is a significant issue for both consumers and financial institutions. This project aims to develop a machine learning model capable of detecting fraudulent transactions based on transaction details. The system utilizes various algorithms such as Logistic Regression, Random Forest to identify whether a transaction is fraudulent or not.


### Dataset

This project uses the Credit Card Fraud Detection dataset from Kaggle, which contains 284,807 transactions made by credit cards in September 2013 by European cardholders. It includes 31 features, including anonymized information about the transaction, with a binary classification label indicating whether the transaction was fraudulent (1) or legitimate (0).

### Key points about the dataset:

Total records: 284,807

Class distribution: Imbalanced (fraudulent transactions are much fewer)

Features: The dataset contains anonymized features (V1, V2, ..., V28) along with time and amount of the transaction.

### Models and Techniques

This project implements several machine learning algorithms to detect fraudulent credit card transactions. Key models and techniques include:

Logistic Regression: A simple linear model for binary classification.

Random Forest: An ensemble learning model to improve prediction accuracy.

## Evaluation Metrics
The evaluation of the model is done using several metrics, including:

Accuracy: The percentage of correct predictions.

Precision: The ratio of true positive predictions to the total predicted positives.

Recall: The ratio of true positive predictions to the total actual positives.

F1 Score: The harmonic mean of precision and recall.


### Acknowledgments

Credit Card Fraud Detection Dataset

Scikit-learn Documentation

Kaggle for providing the dataset

