# Car-Evaluation-Prediction
A decision to buy a car or not according to its physical qualifications is being discussed here.

Dataset: http://archive.ics.uci.edu/ml/datasets/Car+Evaluation

This dataset has 1728 records in which each record represents a car evaluation. Each car evaluation is described with 7 attributes. 6 of the attributes represent car characteristics such as:
1. Buying price
2. Price of maintenance
3. Number of doors
4. Capacity in terms of persons to carry
5. Size of luggage boot
6. Estimated safety of the car

The seventh variable represents the evaluation of the car as:
1. Unacceptable
2. Acceptable
3. Good
4. Very good

In this multi-class classification, I have used Naive Bayes, KNN, Decision Tree, Logistic Regression and Support Vector Machine (SVM) models using cross validation after preparing the data using one-hot encoding and tuning the optimal hyperparameters for each model to predict the car evaluation. I have used Cohen's Kappa score as the scoring metric to compare the results from each model since the data is highly imbalanced (more records of cars in Unacceptable category).

Best Performing Model: Decision Tree (Kappa Score – 0.905)

