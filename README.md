# House Price Prediction using Linear Regression

This project implements a Linear Regression model to predict house prices based on key features such as square footage, number of bedrooms, and number of bathrooms. It demonstrates the application of regression techniques in real-world scenarios, making it ideal for machine learning beginners.

## Features

### Input Features:
- **Square footage of the house**: The total area of the house in square feet.
- **Number of bedrooms**: The count of bedrooms in the house.
- **Number of bathrooms**: The count of bathrooms in the house.

### Prediction Output:
- **Estimated price of the house**: The predicted market price based on the input features.

## Model Evaluation
To assess the performance of the model, the following metrics are used:
- **Mean Squared Error (MSE)**: Measures the average squared difference between the actual and predicted house prices.
- **R² Score**: Indicates the proportion of the variance in the dependent variable (house price) that is predictable from the independent variables.

## Data Visualization
The project includes visualizations to explore relationships between the features and target variable, model residuals, and the overall model fit:
- Scatter plots and correlation heatmaps to understand feature relationships.
- Residual plots to assess the accuracy of predictions.

## Technologies Used
- **Programming Language**: Python
- **Libraries**:
  - `pandas`: For data manipulation and preprocessing.
  - `NumPy`: For numerical operations.
  - `scikit-learn`: For building and evaluating the regression model.
  - `matplotlib` & `seaborn`: For creating visualizations.

## Dataset
The dataset used for this project can be accessed from Kaggle:
- [House Prices: Advanced Regression Techniques Dataset](https://www.kaggle.com/c/house-prices-advanced-regression-techniques/data)
