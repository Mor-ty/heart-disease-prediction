# Heart Disease Prediction

This project aims to predict heart disease presence based on various health parameters using machine learning techniques. We utilize GridSearchCV to optimize hyperparameters and improve model performance.

## Table of Contents
- [Introduction](#introduction)
- [Dataset](#dataset)
- [Requirements](#requirements)
- [Installation](#installation)
- [Usage](#usage)
- [Data Exploration and Visualization](#data-exploration-and-visualization)
- [Data Preprocessing](#data-preprocessing)
- [Model Building](#model-building)
- [Hyperparameter Tuning](#hyperparameter-tuning)
- [Evaluation](#evaluation)
- [Results](#results)
- [Contributing](#contributing)
- [License](#license)

## Introduction
Heart disease is one of the leading causes of death globally. Early prediction and diagnosis can help in taking preventive measures. This project uses machine learning algorithms to predict the likelihood of heart disease in patients based on health metrics such as age, sex, blood pressure, cholesterol levels, etc.

## Dataset
The dataset used in this project is the [Heart Disease UCI dataset](https://archive.ics.uci.edu/ml/datasets/heart+disease). It consists of 303 records and 14 attributes.

## Requirements
- Python 3.6+
- Jupyter Notebook
- NumPy
- Pandas
- Scikit-learn
- Matplotlib
- Seaborn

## Models used 
- Logistic Regression
- Decision Tree
- Random Forest
- Support Vector Machine (SVM)
- K-Nearest Neighbors (KNN)

## RESULTS
After tuning with GridSearchCV, the Random Forest model performed best with:<br>
accuracy: 89.2%<br>
n_estimators: 20
