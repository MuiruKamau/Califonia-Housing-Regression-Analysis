# California Housing Price Prediction

## Project Overview

This project aims to predict California housing prices based on a variety of features using machine learning models. It explores the relationships between house prices and features such as median income, house age, average rooms per household, and more. The analysis is conducted on the California Housing dataset, available through `sklearn.datasets`.

## Dataset

The dataset is derived from the 1990 California census and includes metrics such as:

- Median income
- Housing median age
- Average rooms
- Average bedrooms
- Population
- Average occupancy
- Latitude
- Longitude

The target variable is the median house value for California districts.

## Methodology

The project involves several key steps:

1. **Data Exploration**: Understanding the dataset through statistics and visualizations.
2. **Preprocessing**: Cleaning data and preparing it for modeling.
3. **Model Selection**: Comparing various models to find the best performer. Models evaluated include:
   - Linear Regression
   - Lasso Regression
   - Ridge Regression
   - Decision Tree Regression
   - Random Forest Regression
4. **Model Evaluation**: Using metrics like MSE, R², and RMSE to assess model performance.
5. **Final Model**: Choosing the Random Forest Regression model based on superior performance.

## Installation

To set up the project environment, clone the repository and install the required packages listed in `requirements.txt`:

```bash
git clone <repository-url>
cd <project-directory>
pip install -r requirements.txt
