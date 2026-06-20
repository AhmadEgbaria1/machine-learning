Machine Learning Assignment 2: Linear Regression, Perceptron, and Logistic Regression
Overview
This repository contains the solution for Machine Learning Assignment 2, covering fundamental concepts and implementations of several supervised learning algorithms. The assignment explores Linear Regression with regularization (Ridge and Lasso), the Perceptron algorithm, and Logistic Regression with L1 regularization.

Topics Covered
Linear Regression: Predicting continuous outcomes with a focus on regularization techniques.
Perceptron: A binary classification algorithm for linearly separable data.
Logistic Regression: A probabilistic classification model, including hyperparameter tuning and regularization.
Exploratory Data Analysis (EDA): Understanding data distributions and correlations.
Dataset Information
Question 1 - Linear Regression
Dataset: Energy Efficiency Dataset (UCI Machine Learning Repository)
Description: Predicts energy efficiency (Heat & Cool loadings) based on building attributes (e.g., wall area, glazing area).
Source: https://sharon.srworkspace.com/ml/datasets/hw3/ENB2012_data.csv
Question 2 - Perceptron
Dataset: Synthetic 2D binary classification data.
Description: Used to implement and evaluate the Perceptron algorithm.
Source: https://sharon.srworkspace.com/ml/datasets/hw2/perceptron_data.npy
Question 3 - Logistic Regression
Dataset: Exam scores for binary classification.
Description: Determines if a student passes a course based on two grades.
Source: https://sharon.srworkspace.com/ml/datasets/hw2/exams2.csv
Question 5 - Bonus
Dataset: Toronto Rentals Data
Description: Predicts house prices using a custom L1 loss function.
Source: https://sharon.srworkspace.com/ml/datasets/Toronto_rentals.csv
Assignment Structure
The notebook is organized into the following sections:

Question 1 - Linear Regression: Implements and compares Linear, Ridge, and Lasso regression models, including hyperparameter tuning and analysis of feature correlations.
Question 2 - Perceptron: Implements the Perceptron algorithm, evaluates its performance, and analyzes the effect of batch_size on convergence and accuracy.
Question 3 - Logistic Regression: Implements Logistic Regression with gradient descent, tunes L1 regularization (lambda), and visualizes the decision boundary.
Question 4 - SVM (Theoretical): Addresses theoretical aspects of Support Vector Machines.
Question 5 - Bonus: Implements a custom linear regression model minimizing L1 loss from scratch.
How to Run the Notebook
Open in Google Colab: Click the "Open in Colab" badge (if available) or upload the .ipynb file to Google Colab.
Run All Cells: Go to Runtime > Run all to execute all code cells and reproduce the results, plots, and outputs.
Review Output: Examine the printed outputs, plots, and markdown explanations for each question.
Dependencies
The following Python libraries are used in this notebook:

numpy
pandas
matplotlib
tqdm
scikit-learn (sklearn)
requests
These are typically pre-installed in Google Colab environments. If running locally, ensure you have them installed (pip install numpy pandas matplotlib scikit-learn requests).

Submission Details
Submitted by:
Student 1 Sham Abo Shtya (ID: 322857574)
Student 2 Ahmad Agbaria (ID: 212352504)
Submission Date: 19\05\2025, 23:59.
Important Notes
The code is designed to be clean, concise, and well-commented.
All plots, results, and outputs are included within the notebook cells.
Answers to questions are provided in red text within markdown cells.
