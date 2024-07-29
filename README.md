# Credit Card Fraud Detection

## Overview
The Credit Card Fraud Detection project aims to identify fraudulent transactions using machine learning techniques. This project leverages a dataset (`credit_card.csv`) containing anonymized credit card transactions to build and evaluate models that can detect fraudulent activities. The objective is to develop an effective and efficient system that can assist in preventing financial fraud.

## Dataset
The dataset used in this project, `credit_card.csv`, contains credit card transactions made by European cardholders. The dataset is highly unbalanced, with a small percentage of fraudulent transactions. Features in the dataset have been anonymized using PCA transformation, except for the `Time` and `Amount` features.

- **Time**: Seconds elapsed between this transaction and the first transaction in the dataset.
- **Amount**: Transaction amount.
- **Class**: Target variable, where `1` indicates a fraudulent transaction and `0` indicates a legitimate transaction.

## Features
- **Data Preprocessing:** Handling imbalanced data, feature scaling, and cleaning.
- **Model Building:** Training machine learning models to classify transactions as fraudulent or legitimate.
- **Model Evaluation:** Assessing model performance using metrics like accuracy, precision, recall, F1-score, and AUC-ROC.
- **Visualization:** Visualizing data distribution, feature importance, and model performance.
