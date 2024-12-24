# Car Price Prediction

## Overview
This project predicts the prices of used cars based on features such as car make, year of manufacture, fuel type, and kilometers driven. The project utilizes machine learning algorithms to analyze the dataset and generate accurate predictions.

This repository contains all the code and resources for this project.

## Steps
1. **Data Loading and Exploration**
   - Load the car dataset (`car data.csv`) and perform initial exploration.
2. **Data Cleaning**
   - Handle missing values (if any), encode categorical data, and prepare the dataset for modeling.
3. **Feature Engineering**
   - Create meaningful features for the machine learning model.
4. **Model Development**
   - Train machine learning models to predict car prices.
   - Evaluate model performance using metrics like R² score and mean squared error.
5. **Model Optimization**
   - Fine-tune hyperparameters and improve accuracy.
6. **Prediction**
   - Use the trained model to predict car prices for new data.

## Code
The code for this project is available in the file:

- **Car_Price_Prediction.ipynb**

## Technologies/Tools
- **Programming Language**: Python 3.10
- **Development Environments**: Jupyter Notebook / Google Colab
- **Key Libraries**:
  - pandas (`pip install pandas`)
  - scikit-learn (`pip install scikit-learn`)


![Python](https://img.shields.io/badge/python-3.10-blue)
![Jupyter](https://img.shields.io/badge/jupyter-orange)
![Pandas](https://img.shields.io/badge/pandas-green)
![Scikit-Learn](https://img.shields.io/badge/scikit--learn-orange)


## Dataset
The dataset used in this project is:

- **car data.csv**: A dataset containing 301 records of used cars with attributes such as `Year`, `Selling Price`, `Present Price`, `Fuel Type`, etc.

## Features
The key features in the dataset include:
- **Year**: Year of manufacture
- **Selling_Price**: Price at which the car is sold
- **Present_Price**: Current price of the car
- **Kms_Driven**: Distance driven by the car in kilometers
- **Fuel_Type**: Type of fuel used (Petrol/Diesel/CNG)
- **Seller_Type**: Dealer or individual
- **Transmission**: Manual or Automatic
- **Owner**: Number of previous owners

## Installation
To set up the environment for this project:
1. Install Python 3.10 or later.
2. Install required libraries using pip:
   ```bash
   pip install pandas scikit-learn
