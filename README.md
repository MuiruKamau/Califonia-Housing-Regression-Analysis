# California Housing Price Prediction

## Project Overview
The primary objective of this project is to identify the most effective machine learning model for predicting California housing prices. We aim to compare various regression models on their accuracy and efficiency in handling the dataset derived from the 1990 California census.

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
