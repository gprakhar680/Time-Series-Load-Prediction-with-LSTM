# Time-Series-Load-Prediction-with-LSTM
Short-term electricity demand forecasting using LSTM with engineered time-series features including lags, rolling stats, and cyclical encoding. Trained on historical load and weather data for accurate one-step predictions. Applications in smart grids, renewable integration, and energy planning
Features
Data Preprocessing

Date-time parsing & indexing

Cyclical encoding for hour, day, and month

Lag features & rolling mean/standard deviation

Robust scaling to handle outliers

Model

Stacked LSTM layers for long-term dependencies

Dense layer for feature interaction

Dropout for regularization

Output layer for one-step-ahead predictions

Evaluation

Metrics: RMSE, MSE

Visualization of predictions vs. actual values
