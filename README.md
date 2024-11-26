# Iris Classification with Logistic Regression

This project demonstrates a basic implementation of logistic regression for classifying Iris flower species using the famous Iris dataset. The dataset contains 150 samples of Iris flowers, each with four features: sepal length, sepal width, petal length, and petal width. The task is to classify the flowers into three species: Setosa, Versicolour, and Virginica.

## Features of the Project
- **Dataset**: Iris dataset, included in `sklearn.datasets`.
- **Model**: Logistic Regression from `sklearn.linear_model`.
- **Evaluation**: Accuracy score from `sklearn.metrics`.

## Code Overview
The main steps in the project are:
1. **Loading the Dataset**: Using `load_iris()` from `sklearn.datasets`.
2. **Splitting Data**: Training and testing sets created with an 80-20 split using `train_test_split`.
3. **Model Training**: Logistic Regression model is trained on the training set.
4. **Prediction**: Model predicts on the test set.
5. **Evaluation**: Accuracy of the model is calculated and displayed.

## Requirements
- Python 3.x
- Scikit-learn

Install the required library with:
```bash
pip install scikit-learn
