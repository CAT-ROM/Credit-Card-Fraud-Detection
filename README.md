# Credit-Card-Fraud-Detection

## Project Overview 📊

This project focuses on detecting fraudulent credit card transactions using machine learning techniques. The goal is to build a model that can accurately predict whether a credit card transaction is legitimate or fraudulent based on a set of transaction features.

## Objective 🎯

- Build a classification model that can distinguish between fraudulent and legitimate transactions.
- Utilize machine learning techniques to create a highly accurate fraud detection system.
- Evaluate and compare multiple machine learning models to identify the best one for fraud detection.

## Problem Statement 🔍

Credit card fraud is a growing concern worldwide. Financial institutions and credit card companies strive to detect and prevent fraudulent transactions. With the vast number of transactions being processed daily, it's impossible for humans to manually check each one. Therefore, an automated fraud detection system is essential to help minimize losses and protect users.

The objective of this project is to develop an effective model that can identify fraudulent transactions with high accuracy based on transactional data.

## Datasets 📂

The dataset used for this project is the **Credit Card Fraud Detection** dataset, which is publicly available on Kaggle. The dataset consists of credit card transactions made by European cardholders in September 2013, where the task is to predict fraudulent transactions.

- **Dataset Source:** Kaggle: Credit Card Fraud Detection Dataset

### Data Description 🚀

- The dataset contains **284,807** transactions, with **492** frauds (**0.172%** of the total data).
- Features are anonymized for privacy protection, except for the **"Amount"** and **"Time"** columns.
- The target variable is **Class**, where **0** indicates a legitimate transaction and **1** indicates a fraudulent one.

## Key Findings & Results 🏆

### 1. Model Evaluation 📈

- After training several machine learning models, the **Random Forest Classifier (RFC)** and **Gradient Boosting (GB)** models provided the best results in terms of accuracy, precision, and recall.
- The models successfully identified fraudulent transactions with high precision, despite the highly imbalanced dataset.

### 2. Performance Metrics 📊

- **Accuracy:** 98.8% ✔️
- **Precision:** 94% 🎯
- **Recall:** 80% 🔍
- **F1-Score:** 86% ⚖️

These metrics demonstrate the model’s effectiveness at detecting fraudulent transactions while minimizing false positives.

### 3. Feature Importance 💡

- Key features contributing to fraud detection included the anonymized features (**V1**, **V2**, **V3**, etc.) and the transaction **Amount**, with **V1** and **V2** playing a significant role in the prediction.

### 4. Contributions & Improvements 🔧

This project can be extended by:
- Applying advanced techniques such as **SMOTE** (Synthetic Minority Over-sampling Technique) to handle the class imbalance issue.
- Experimenting with deep learning techniques, such as **Neural Networks**, for potentially improved performance.
- Implementing **real-time fraud detection systems** that can analyze transactions as they occur.

## License 📜

This project is licensed under the **MIT License** - see the LICENSE file for details.

## Acknowledgements 🙏

- The dataset is provided by the **UCI Machine Learning Repository** and is available for public use.
- Many thanks to the **Kaggle** community and **Codsoft** for sharing their insights and providing resources to solve similar problems.
