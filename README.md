# Weekly Sales Forecasting with XGBoost

This project forecasts weekly sales for different store-product combinations using **XGBoost**. The dataset contains historical daily sales data, which is aggregated into weekly sales, and the model predicts future sales using lag features and rolling averages.

## Features

- Aggregation of daily sales to weekly sales.
- Feature engineering:
  - Year, month, week of year
  - Lag features (lag_1, lag_2)
  - Rolling mean over 3 weeks
- Label encoding for categorical variables (product family).
- Model training using XGBoost Regressor.
- Performance evaluation with:
  - Mean Absolute Error (MAE)
  - Root Mean Squared Error (RMSE)

## Output

✅ Model Performance:
Mean Absolute Error (MAE): 123.45
Root Mean Squared Error (RMSE): 234.56

