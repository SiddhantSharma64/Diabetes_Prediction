# Machine Learning Project: Predicting Diabetes with a Flask Web Application

## Project Overview
This project aims to predict the onset of diabetes based on diagnostic measures. I have used the Pima Indians Diabetes Dataset from the UCI Machine Learning Repository. The predictions are made available through a Flask web application.

## Dataset
The dataset consists of several medical predictor variables and one target variable (Outcome). Predictor variables include the number of pregnancies the patient has had, their BMI, insulin level, age, and more.

## Requirements
- Python 3.12
- Libraries: pandas, numpy, sklearn, matplotlib, seaborn, Flask

## Data Preprocessing
The data is preprocessed by handling missing values and scaling the features.

## Evaluation
Model performance is evaluated using metrics such as accuracy, precision , recall and F1 score.

## Flask Application
The Flask web application provides a user-friendly interface to input medical data and get predictions for diabetes onset. To run the application locally:

- Install the required dependencies.

- Run the Flask application by executing python application.py in your terminal.

- Access the application via the provided URL (http://127.0.0.1:5000).