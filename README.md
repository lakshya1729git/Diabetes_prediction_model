Diabetes Prediction using Machine Learning
A Machine Learning project that predicts whether a person has diabetes or not based on several medical parameters. Built using Python and Scikit-Learn, this model is simple, fast, and effective for binary classification tasks.

Project Overview
Diabetes is a major health concern worldwide. Early diagnosis can help prevent severe health issues.
This project trains a Support Vector Machine (SVM) classifier on the PIMA Indians Diabetes dataset to predict whether a person is diabetic or not.

The system allows users to input their health data and instantly receive a prediction.

Technologies and Libraries Used
Python

Numpy

Pandas

Scikit-Learn

Google Colab / Jupyter Notebook

Dataset Information
The dataset used is the PIMA Indians Diabetes Database, sourced from Kaggle. It consists of 768 entries with 9 columns.
The target column 'Outcome' contains 0 (non-diabetic) or 1 (diabetic).

Project Workflow
Load and explore the dataset using Pandas.

Preprocess the data:

Standardize feature values using StandardScaler.

Split data into training and testing sets (80/20 split).

Train a Support Vector Machine (SVM) classifier with a linear kernel.

Evaluate the model using accuracy scores on both training and testing data.

Build a simple prediction system to classify new data points.
