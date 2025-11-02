# Car Price Prediction — Regression Analysis and Model Selection

This project applies multiple machine learning regression techniques to predict car prices based on their features.  
The dataset includes engine capacity, horsepower, cylinders, car brand, country, and other car specifications.  
The goal is to build an accurate model that generalizes well and avoids overfitting.

## Dataset
- 6,308 original car records.
- Target variable: Car Price (standardized to USD)
- Numerical + categorical features
- Issues handled:
  - Missing target values
  - Inconsistent engine units (L vs CC)
  - Encoding categorical variables
  - Normalization with Z-score

## Models Implemented
### Linear Models
- Simple Linear Regression
- Closed-form Linear Regression
- Gradient Descent Regression
- LASSO Regression (L1)
- Ridge Regression (L2)

### Nonlinear Models
- Polynomial Regression (Degree 2–6)
- RBF Kernel Regression (SVR)

## Key Techniques
- Grid search hyperparameter tuning
- Train/validation/test split: 60% / 20% / 20%
- Feature selection (forward selection)

## Results
The **RBF Regression model** achieved the best generalization:

## Project Structure
- `car_price_regression.ipynb` — Full implementation

## Author
- Sondos Qasarwa
- Sarah Hassouneh 
