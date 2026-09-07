# California Housing Price Prediction & Model Optimization

This project evaluates multiple regression algorithms on the California Housing dataset to identify optimal predictive architectures based on RMSE and $R^2$ performance metrics.

## Key Features
- **Feature Scaling**: Centered and scaled 8 input attributes using `StandardScaler`.
- **Model Comparison**: Benchmarked baseline `LinearRegression`, regularized `Ridge`, and non-linear `DecisionTreeRegressor`.
- **Diagnostics**: Evaluated residual distributions and boundary behaviors.

## Results Summary
| Model | RMSE | $R^2$ Score |
| :--- | :--- | :--- |
| Linear Regression | 0.7456 | 0.5758 |
| Ridge Regression | 0.7456 | 0.5758 |
| **Decision Tree ($depth=5$)** | **0.7397** | **0.5825** |

