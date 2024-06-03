# Credit-Card-Fraud-Detection

This project demonstrates a machine learning approach to detect fraudulent credit card transactions using a dataset of anonymized transactions.

## Introduction

Credit card fraud detection is crucial for financial institutions to prevent financial losses. This project uses machine learning techniques to identify fraudulent transactions in a dataset of credit card transactions.

## Dataset

The dataset used in this project is the [Credit Card Fraud Detection dataset](https://www.kaggle.com/datasets/mlg-ulb/creditcardfraud) from Kaggle. It contains transactions made by credit cards in September 2013 by European cardholders. The dataset presents transactions that occurred in two days, with 492 frauds out of 284,807 transactions.

## Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/fazaulfath/Credit-Card-Fraud-Detection.git
   cd Credit-Card-Fraud-Detection

2. Install the required libraries:
   ```bash
   pip install -r requirements.txt

## Usage

1. Ensure you have the dataset creditcard.csv in the project directory.
2. Run the Jupyter notebook or the Python script to execute the code:
   ```bash
   jupyter notebook credit_card_fraud.ipynb

## Methodology

1. Importing Libraries: Import necessary libraries for data manipulation, visualization, and machine learning.
2. Reading Data: Load the dataset and display the first few rows to understand its structure.
3. Data Description: Describe the data to identify which columns need further processing.
4. Data Visualization: Plot the distribution of transaction amounts against the class labels to identify patterns.
5. Data Scaling: Normalize the Time and Amount columns to handle outliers and prepare for modeling.
6. Dataset Visualization: Visualize the class distribution to identify the imbalance in the dataset.
7. Dataset Balancing: Balance the dataset by under-sampling the majority class to have an equal number of fraud and non-fraud transactions.
8. Train-Test Split: Split the dataset into training and testing sets to evaluate the model's performance.
9. Model Training: Train a Logistic Regression model on the training data.
10. Model Evaluation: Evaluate the model using classification metrics, confusion matrix, and accuracy score.

## Results

The results section includes the performance metrics of the model such as precision, recall, F1-score, confusion matrix, and accuracy. Logistic Regression was chosen for this use case, providing the best results compared to other models like Random Forest and Decision Tree Classifiers.
