# IA2A Peru Bank Credit Risk Evaluation Competition
Welcome to the IA2A Peru Bank Credit Risk Evaluation Competition repository. This project contains notebooks for preprocessing data, training machine learning models, and generating predictions for the competition. The project includes two approaches: one using XGBoost and another using TensorFlow for more flexibility and control over the model architecture and hyperparameters.

- Name: Kevin Juan Román Rafaele
- LinkedIn: https://www.linkedin.com/in/kevin-juan-r-997530117/
- Email: mrredsky.2095@gmail.com
- License: MIT License

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
```pip install pandas numpy scikit-learn xgboost tensorflow jupyter```

## Data Preprocessing
The data preprocessing involves the following steps:
1. Loading data from CSV files.
2. Handling values using SQL queries.
3. Encoding categorical variables.
4. Scaling numerical features.

## Model Training and Evaluation
### XGBoost Model
The XGBoost model notebook (I2A2_Peru.ipynb) includes:
1. Training an XGBoost model to determine feature importance.
2. Selecting the top N important features.
3. Training and evaluating the model using the selected features.
4. Generating predictions and preparing the submission file.

### TensorFlow Model
The TensorFlow model notebook (I2A2_Peru_tf.ipynb) includes:
1. Training an XGBoost model to determine feature importance.
2. Selecting the top N important features.
3. Building and training a neural network using TensorFlow.
4. Evaluating the model's performance using Mean FBeta-Score.
5. Generating predictions and preparing the submission file.

## Usage
To use the notebooks, follow these steps:
1. Clone the repository:
```
git clone https://github.com/yourusername/ia2a-peru-bank-credit-risk-evaluation.git
cd ia2a-peru-bank-credit-risk-evaluation
```
2. Launch jupyter notebook:
```
jupyter notebook
```
3. Open the desired notebook (I2A2_Peru.ipynb or I2A2_Peru_tf.ipynb) and run the cells sequentially.

## Results
The models' performances are evaluated using the Mean FBeta-Score. The results and the final submission files are generated within the notebooks. The submission scores from both models are around 0.55.

## Contributing
Contributions are welcome! If you have any improvements or suggestions, feel free to open an issue or submit a pull request.
