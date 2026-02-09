# Boston House Price Prediction

This project builds a simple **multiple linear regression model** to predict house prices in Boston using Python and scikit-learn.

The model estimates housing value based on:
- Average number of rooms
- Distance from employment centers

## Dataset
- File: `Boston House Prices.csv`
- Size: 506 rows
- Features used:
  - `Rooms` – average number of rooms per dwelling
  - `Distance` – distance to employment centers
  - `Value` – median house price (target variable)

## Tools & Libraries
- **Python**
- **Pandas** – data loading and preprocessing
- **scikit-learn** – linear regression modeling

## Methodology
1. Loaded and explored the dataset
2. Selected independent variables (`Rooms`, `Distance`)
3. Trained a **Linear Regression** model
4. Generated predictions
5. Evaluated model performance using **R² score**
6. Extracted model coefficients and intercept
7. Formulated the regression equation

## Model Performance
- **R² Score:** ~0.50  
  Indicates that the model explains about 50% of the variance in house prices.

## Linear Regression Equation
Value = 8.80 × Rooms + 0.49 × Distance − 34.64


## How to Run
1. Clone the repository
2. Ensure `Boston House Prices.csv` is in the project directory
3. Run the notebook cells in order

## Notes
This project is intended as an introductory example of regression modeling and does not include feature scaling, validation splits, or advanced evaluation techniques.
