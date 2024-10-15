# Linear Regression Model to Predict House Prices

This repository contains a project aimed at predicting **house prices** using the **California Housing Dataset**. The dataset is based on housing data from the 1990 U.S. Census, focusing on predicting the **median house value** using features such as median income, total rooms, population, and more. The project involves two machine learning models: **Linear Regression** and **Random Forest**.

## Dataset

The dataset contains the following columns:

| Column Name           | Description                                                 |
|-----------------------|-------------------------------------------------------------|
| `longitude`           | Longitude of the district (geographical coordinate)         |
| `latitude`            | Latitude of the district (geographical coordinate)          |
| `housing_median_age`  | Median age of the houses in the district                    |
| `total_rooms`         | Total number of rooms in all houses in the district         |
| `total_bedrooms`      | Total number of bedrooms in all houses in the district      |
| `population`          | Population of the district                                  |
| `households`          | Total number of households in the district                  |
| `median_income`       | Median income of the households in the district             |
| `median_house_value`  | Median house value (target variable)                        |
| `ocean_proximity`     | Proximity to the ocean (categorical variable)               |

## Models

### 1. Linear Regression
A simple regression model that assumes a linear relationship between the features and the target variable (median house value).

### 2. Random Forest
A more complex ensemble model that builds multiple decision trees and averages their predictions for better accuracy and handling non-linear relationships.

## Workflow

1. **Data Preprocessing**:
   - Handle missing values and outliers.
   - Normalize/scale the data if required.
   - Split the data into training and testing sets.

2. **Model Training**:
   - Train both Linear Regression and Random Forest models on the training set.
   - Evaluate their performance using metrics such as **Mean Squared Error (MSE)** and **R-squared (R²)** on the test set.

3. **Model Comparison**:
   - Compare the performance of the two models to identify which one offers better accuracy.

## How to Run

1. Clone the repository:
   ```bash
   git clone https://github.com/AHSANATIQ98/Linear-Regression-Model-to-predict-House-Prices.git
