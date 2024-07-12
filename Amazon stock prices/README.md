# Simple RNN for Forecasting Amazon Stock Prices

This repository contains a Jupyter Notebook that demonstrates how to use a Simple Recurrent Neural Network (RNN) to forecast Amazon stock prices. The notebook covers the entire process from data preparation to model training and evaluation.

## Table of Contents
- [Introduction](#introduction)
- [Dataset](#dataset)
- [Dependencies](#dependencies)
- [Notebook Overview](#notebook-overview)
  - [1. Import Libraries](#1-import-libraries)
  - [2. Load Dataset](#2-load-dataset)
  - [3. Data Preprocessing](#3-data-preprocessing)
  - [4. Build and Compile the Model](#4-build-and-compile-the-model)
  - [5. Train the Model](#5-train-the-model)
  - [6. Evaluate the Model](#6-evaluate-the-model)
- [Results](#results)
- [Conclusion](#conclusion)

## Introduction
Time series forecasting is a crucial task in finance and other domains where predicting future values is important. This project uses a Simple RNN to predict Amazon stock prices based on historical data.

## Dataset
The dataset used in this project is the historical stock prices of Amazon, which can be obtained from various financial data sources. 

## Dependencies
- Python 3.x
- pandas
- numpy
- matplotlib
- seaborn
- scikit-learn
- tensorflow

You can install the dependencies using the following command:
```bash
pip install pandas numpy matplotlib seaborn scikit-learn tensorflow
```
## Notebook Overview
### 1. Import Libraries
The first section of the notebook imports the necessary libraries for data manipulation, visualization, and model building.

### 2. Load Dataset
This section loads the Amazon stock prices dataset and performs initial exploration to understand its structure.

### 3. Data Preprocessing
Data preprocessing steps include handling missing values, feature scaling, and creating sequences for the RNN model.

### 4. Build and Compile the Model
In this section, we build a Simple RNN model using TensorFlow and compile it with an appropriate loss function and optimizer.

### 5. Train the Model
The model is trained on the prepared dataset, and the training history is recorded for later analysis.

### 6. Evaluate the Model
After training, the model's performance is evaluated using metrics like Mean Absolute Error (MAE) and visualized using plots.

## Results
The notebook includes plots of the training and validation loss over epochs, as well as the predicted vs. actual stock prices.

## Conclusion
This project demonstrates the use of a Simple RNN for time series forecasting of stock prices. While the model provides a basic introduction to RNNs, further improvements can be made by experimenting with more advanced architectures and hyperparameter tuning.

Feel free to explore the notebook and modify the code to suit your needs. Happy forecasting!

