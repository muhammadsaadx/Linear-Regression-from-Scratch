# Linear Regression 

## Overview
This repository implements a Linear Regression model to analyze and predict numerical data. It includes steps for data preprocessing, visualization, model training, and evaluation.

## Features
- Loads and explores a dataset
- Handles missing values and duplicates
- Visualizes data distributions and correlations
- Implements a Linear Regression model
- Evaluates model performance using common metrics

## Requirements
Ensure you have the following Python libraries installed:
```bash
pip install pandas numpy matplotlib seaborn scipy scikit-learn
```

## Usage
1. Place the dataset file (`dataset.csv`) in the same directory as the notebook.
2. Open and run the `LinearRegression.ipynb` notebook in Jupyter Notebook or JupyterLab.
3. Follow the structured steps in the notebook to understand and analyze the dataset.

## Data Preprocessing
- Reads the dataset from a CSV file
- Checks for missing values and removes them
- Selects numerical columns for analysis
- Generates summary statistics and visualizations

## Model Training
- Splits data into training and testing sets
- Trains a Linear Regression model
- Plots regression results and residuals

## Evaluation Metrics
- Mean Squared Error (MSE)
- R-squared Score (R²)

## Visualization
- Histograms and distribution plots
- Scatter plots with regression lines
- Residual plots

