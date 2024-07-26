# IA2A Peru Bank Credit Risk Evaluation Competition
Welcome to the IA2A Peru Bank Credit Risk Evaluation Competition repository. This project contains scripts and notebooks to preprocess data, train machine learning models, and generate predictions for the competition. The project includes two approaches: one using XGBoost and another using TensorFlow for more flexibility and control over the model architecture and hyperparameters.

License: MIT License
Author: Kevin Juan Román Rafaele

## Table of Contents
1. Project Overview
2. Requirements
3. Data Preprocessing
4. Model Training and Evaluation
   - XGBoost Model
   - TensorFlow Model
5. Usage
6. Results

## Project Overview
This repository addresses the IA2A Peru Bank Credit Risk Evaluation competition, which aims to predict the likelihood of a client defaulting on a loan. The project involves data preprocessing, feature selection using XGBoost, and training machine learning models using both XGBoost and TensorFlow.

## Requirements
Ensure you have the following packages installed:
- Python 3.x
- pandas
- numpy
- scikit-learn
- xgboost
- tensorflow
- sqlite3

You can install the required packages using:
pip install pandas numpy scikit-learn xgboost tensorflow sqlite3

## Data Preprocessing
The data preprocessing involves the following steps:
1. Loading Data: The training and test datasets are loaded from CSV files.
2. SQL Queries: Data manipulation is performed using SQL queries to handle missing values and preprocess the data.
3. Encoding Categorical Variables: Categorical variables are encoded as numeric values.
4. Feature Scaling: Features are scaled using StandardScaler.

## Model Training and Evaluation
### XGBoost Model
The first approach uses XGBoost for training and evaluating the model in I2A2_Peru.ipynb. The steps include:
1. Splitting the data into training and validation sets.
2. Training an XGBoost model on the training set.
3. Evaluating the model using Mean FBeta-Score.
4. Generating predictions for the test set and preparing the submission file.

### TensorFlow Model
The second approach integrates XGBoost for feature importance and TensorFlow for training a neural network model in I2A2_Peru_tf.ipynb. The steps include:
1. Using XGBoost to determine feature importance and selecting the top N features.
2. Building and training a neural network using TensorFlow.
3. Evaluating the model using Mean FBeta-Score.
4. Generating predictions for the test set and preparing the submission file.

## Results
The performance of the models is evaluated using the Mean FBeta-Score. The results will be printed in the console after running the scripts.
