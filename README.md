# Vehicle Price Prediction

## Overview

The Vehicle Price Prediction project aims to create a predictive model that estimates vehicle prices based on various features. The project utilizes machine learning techniques to analyze a dataset of vehicles, preprocess the data, and build regression models that predict prices accurately.

## Table of Contents

- [Usage](#usage)
- [Features](#features)
- [Data](#data)
- [Models](#models)
- [Results](#results)

## Usage

1. Load the dataset by placing it in the project directory.
2. Preprocess the data, including handling missing values and scaling features.
3. Train the model using the training data.
4. Predict the test set and evaluate the model's performance.

The detailed workflow and instructions are in the `main.py` file.

## Features

- Data cleaning and preprocessing
- Handling missing values using advanced imputation techniques
- Feature scaling using standardization
- Multiple regression models implemented, including Random Forest, Gradient Boosting, and Stacking Regression
- Evaluation of model performance using cross-validation and mean absolute error

## Data

The dataset used in this project contains various features of vehicles, including but not limited to:

- Brand
- Vehicle Model
- Manufacturing Year
- Odometer reading
- Fuel type
- Number of airbags
- Price (target variable)

Check the `train2.csv` and `Test2.csv` files for the training and testing datasets.

## Models

This project employs several regression models, including:

- Random Forest Regressor
- Gradient Boosting Regressor
- KNeighbors Regressor
- Support Vector Regressor
- Stacking Regressor (combination of base models)

## Results

The results of the predictions can be found in the `Prediction7.csv` file. The performance of each model is evaluated, and the final predictions are generated.

