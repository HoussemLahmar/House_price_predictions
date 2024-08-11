# House Price Prediction with `Random Forest`

This project involves predicting house prices using a `RandomForestRegressor` modelto predict house prices based on features like living area, floor space, year built, and overall quality.. The dataset used is from a Kaggle competition. The project includes data preprocessing with pandas, feature scaling, and model evaluation using R-squared. The final predictions are saved to a CSV file for submission.

## Project Overview

The aim of this project is to predict the sales price for each house in the test set using features extracted from the provided dataset. The project follows the following steps:

1. **Load the Dataset**: Load the data using Pandas and take a first look at the structure and sample entries.

2. **Data Cleaning**: Handle missing data by dropping columns with NaN values and exclude object type columns that may cause issues with model fitting.

3. **Feature Selection**: Identify and select features that have a strong correlation with the target variable (SalePrice).

4. **Data Splitting**: Use sklearn's `train_test_split` to divide the data into training and validation sets.

5. **Model Training**: Train a RandomForestRegressor model on the training data.

6. **Model Evaluation**: Evaluate the model using the R-squared metric and visualize feature distribution to check normality.

7. **Normalization/Standardization**: Implement data scaling to improve model performance and Kaggle scores.

## Getting Started

### Prerequisites

To run this project, you'll need the following Python packages:

- pandas
- numpy
- seaborn
- matplotlib
- sklearn

## Results

The R-squared score indicates a decent level of prediction accuracy, but there is room for further optimization.

## Acknowledgments

- Dataset: [Kaggle House Price Competition](https://www.kaggle.com/c/house-prices-advanced-regression-techniques)
- Libraries: pandas, numpy, sklearn, seaborn, matplotlib

