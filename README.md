# 🏠 House Price Prediction

## Overview
Built a House Price Prediction model using 
Linear Regression on California Housing Dataset.

## Results
| Metric    | Value          |
|-----------|----------------|
| Algorithm | Linear Regression |
| R² Score  | 0.6254         |
| RMSE      | $70,060        |
| Dataset   | California Housing |

## Steps Followed
- Loaded and explored dataset
- Handled missing values (total_bedrooms)
- Encoded categorical feature (ocean_proximity)
- Split data into Train (80%) and Test (20%)
- Trained Linear Regression model
- Evaluated using R², MSE, RMSE

## Visualizations
- ✅ Feature Importance Chart
- ✅ Actual vs Predicted Plot
- ✅ Residual Plot

## Key Findings
- median_income is the strongest predictor
  of house price
- Linear Regression achieved R² = 0.625
- Residual plot shows the model struggles 
  with high-value houses (heteroscedasticity)
- This is expected behavior for Linear 
  Regression on complex housing data

## Limitations & Next Steps
- Linear Regression has limits with 
  non-linear data
- Plan to implement Random Forest model
  to improve R² score to 0.80+

## Technologies Used
- Python
- Pandas
- NumPy
- Scikit-learn
- Matplotlib
- Jupyter Notebook

## Dataset
California Housing Dataset
