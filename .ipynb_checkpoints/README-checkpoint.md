# House Price Prediction using Linear Regression

## Overview
This project aims to predict house prices using the California Housing dataset. We use a Linear Regression model to understand the relationship between various features and the target variable (house prices).

## Dataset
The California Housing dataset is available in the `sklearn` library. It contains information collected from the 1990 California census. Each row in the dataset represents a block group or district in California.

## Features
- `MedInc`: Median income in block group
- `HouseAge`: Median house age in block group
- `AveRooms`: Average number of rooms per household
- `AveBedrms`: Average number of bedrooms per household
- `Population`: Block group population
- `AveOccup`: Average number of household members
- `Latitude`: Block group latitude
- `Longitude`: Block group longitude

## Target
- `MedHouseVal`: Median house value for California districts

## Steps
1. Import Libraries
2. Load Dataset
3. Data Exploration
4. Data Preprocessing
5. Train-Test Split
6. Model Training
7. Model Evaluation
8. Predictions

## Installation
To run this project, you need Python installed on your system. You can install the required libraries using the `requirements.txt` file.

```bash
pip install -r requirements.txt
