# Second-Hand Car Sales Analysis

This project explores a second-hand car sales dataset and builds regression models to predict car prices based on features such as engine size, mileage, and year of manufacture.

## Project Overview

The notebook performs:
- Data loading and inspection.
- Missing value handling.
- Data type checking.
- Regression model training.
- Model evaluation using R2, MAE, and RMSE.
- Comparison of linear regression and polynomial regression.

## Dataset

The dataset contains car listing information such as:
- Manufacturer
- Model
- Engine size
- Fuel type
- Year of manufacture
- Mileage
- Price

## Features Used

The project focuses on these numerical features:
- Engine size
- Mileage
- Year of manufacture

The target variable is:
- Price

## Models Used

- Linear Regression
- Polynomial Regression
- Random Forest Regressor
- MLP Regressor
- Clustering methods for exploratory analysis

## Evaluation Metrics

The models are evaluated using:
- R2 Score
- Mean Absolute Error (MAE)
- Root Mean Squared Error (RMSE)

## Project Structure

```text
Second-Hand-Car-Sales.ipynb
car_sales_data.csv
README.md
```

## Requirements

Install the required Python libraries before running the notebook:

```bash
pip install pandas numpy matplotlib seaborn scikit-learn tensorflow
```

## How to Run

1. Clone the repository.
2. Make sure `car_sales_data.csv` is in the same folder as the notebook.
3. Open `Second-Hand-Car-Sales.ipynb` in Jupyter Notebook or VS Code.
4. Run the cells from top to bottom.

## Results

The notebook compares model performance across different features and regression approaches to identify the best prediction method.

## Notes

- The dataset should stay in the same directory as the notebook for the file loading step to work correctly.
- Some cells may take longer to run depending on your machine and dataset size.
