#Thyroid Disease Detection using Multi-Layer Perceptron

Overview
This project develops a thyroid disease detection system using a Multi-Layer Perceptron (MLP) neural network. The goal is to classify patients accurately as having thyroid disease or not based on features extracted from their medical records. Additionally, logistic regression serves as a baseline model for comparison.

Dataset Information
The dataset used in this project is sourced from the Garavan Institute. It contains features and labels corresponding to thyroid disease diagnosis.

Project Workflow
Data Preprocessing:

Handling missing values with mean imputation and data type conversions.
Feature encoding and removal of irrelevant columns like TBG and referral source.
Scaling features using StandardScaler.
Exploratory Data Analysis (EDA):

Summarized key statistics.
Identified and addressed null values and duplicate records.
Model Development:

Baseline Model: Logistic Regression achieved 96.87% accuracy.
MLP Neural Network: A neural network with one hidden layer achieved 99.1% accuracy after 100 epochs.
Improved MLP with additional hidden layers and ReLU activation.
Evaluation:

Metrics: Accuracy and F1 Score.
Confusion matrix visualization for performance insights.
Results
The MLP model achieved the following metrics:

Accuracy: 99.1%
F1 Score: 0.99
The logistic regression baseline achieved an accuracy of 96.87%, which was significantly improved by the MLP.


