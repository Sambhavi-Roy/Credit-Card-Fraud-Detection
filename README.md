# Credit Card Fraud Detection

This project aims to build machine learning models to detect fraudulent credit card transactions. The dataset used is the Credit Card Fraud Detection dataset available on Kaggle.


## Table of Contents

- [Introduction](#introduction)
- [Features](#features)
- [Installation](#installation)
- [Usage](#usage)
- [Results](#results)
- [Contributing](#contributing)
- [References](#references)


## Introduction

Credit card fraud is a significant issue in the financial industry. Detecting fraudulent transactions is critical for minimizing financial losses and protecting users' accounts. This project utilizes Random Forest and Logistic Regression models to identify fraudulent transactions.


## Features

- Data preprocessing and analysis
- Visualization of data distribution and correlation
- Implementation of Random Forest and Logistic Regression classifiers
- Model evaluation with various metrics including accuracy, precision, recall, F1-score, and Matthews correlation coefficient
- Use of balanced class weights to handle class imbalance
- Feature scaling for improved Logistic Regression performance


## Installation

1. Clone the repository:
   
   git clone https://github.com/Sambhavi-Roy/Credit-Card-Fraud-detection.git


## Usage

Load the dataset:

Ensure the creditcard.csv file is placed in the project directory or provide the correct path to the file.


Run the script:

python fraud_detection.py


The script will:

- Load and preprocess the data
- Display data insights and visualizations
- Train and evaluate Random Forest and Logistic Regression models
- Output evaluation metrics and confusion matrices


## Results

- Random Forest Classifier:

Accuracy: 0.995

Precision: 0.97

Recall: 0.76

F1-Score: 0.85


- Logistic Regression:

Accuracy: 0.976

Precision: 0.06

Recall: 0.92

F1-Score: 0.12


## Contributing

Contributions are welcome! Please open an issue or submit a pull request for any improvements or bug fixes.


## References

https://www.geeksforgeeks.org/ml-credit-card-fraud-detection/

