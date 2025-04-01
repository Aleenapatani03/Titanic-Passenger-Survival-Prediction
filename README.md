# Titanic Passenger Survival Prediction

This project aims to predict the survival of passengers aboard the Titanic using machine learning classification models. We have implemented several classification algorithms to determine which model performs the best based on accuracy, precision, recall, and F1-score.

## Introduction

The Titanic dataset consists of information about passengers aboard the Titanic, including whether they survived or not. The task is to predict whether a passenger survived based on various features such as age, sex, class, and others.

## Data Preprocessing

Steps taken in data preprocessing:
1.Loading the Dataset:

We used the Titanic dataset from Kaggle, train.csv, for this project.

2.Handling Missing Data:

Age: We filled missing values in the 'Age' column with the median value of the column.

Embarked: We filled missing values in the 'Embarked' column with the most frequent value (mode).

3.Feature Engineering:

Label Encoding: We encoded categorical features such as 'Sex' and 'Embarked' using LabelEncoder to convert them into numerical form.

4.Feature Selection:
The following features were selected for prediction:

Pclass: The passenger class (1, 2, 3)

Sex: Gender of the passenger

Age: Age of the passenger

SibSp: Number of siblings/spouses aboard

Parch: Number of parents/children aboard

Fare: The fare the passenger paid

Embarked: The port where the passenger boarded (C = Cherbourg; Q = Queenstown; S = Southampton)

## Modeling
Several classification algorithms were implemented to predict the survival of passengers:

1.Logistic Regression

2.Random Forest Classifier

3.Support Vector Machine(SVM)

4.Decision Tree Classifier

5.Naive Bayes

6.K-Nearest Neighbors (KNN)

Each model was trained and evaluated to determine the best performing one.

## Model Evaluation
After training the models, the performance was evaluated using:

Accuracy: The proportion of correct predictions.

## Conclusion

After evaluating all models, the Support Vector Machine(SVM) performed the best, achieving the highest accuracy. It was the most effective model for predicting Titanic survival based on the given features.




