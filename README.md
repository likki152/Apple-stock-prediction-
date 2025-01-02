# Apple-stock-prediction

## Project Overview
This project aims to predict the Adjusted Close price of Apple stock using historical data and advanced machine learning techniques within a big data framework. The implementation utilizes models such as Linear Regression, Random Forest, Decision Trees, and Gradient Boosting Regressor, evaluated using the SMAPE metric. By incorporating market features and applying robust preprocessing methods, this project provides actionable insights into stock price movements.

## Problem Statement
Accurate stock price prediction is essential for financial decision-making but is challenging due to factors like market volatility and economic conditions. This project tackles these complexities using a machine learning-based approach for time series forecasting.

## Goals
- Forecast Apple’s Adjusted Close price using historical data from 2012 to 2023.
- Handle non-stationarity through price difference transformations.
- Deliver insights that benefit various stakeholders, including investors, analysts, and financial institutions.

## Stakeholders
1. **Individual Investors** - To support informed trading and investment decisions.
2. **Financial Analysts** - To augment traditional analysis methods.
3. **Financial Institutions** - To integrate predictions into trading systems and risk assessment models.

## Data Sources
- **Yahoo Finance**: Historical stock data for Apple.
- **FRED**:
  - VIX Volatility Index (VIXCLS).
  - US Bond Yield Data (BAMLH0A0HYM2).

## Methodology
1. **Data Preprocessing**:
   - Feature engineering: Lag variables, rolling statistics, and log transformations.
   - Stationarity adjustments using price differences.
2. **Model Training and Tuning**:
   - Applied Linear Regression, Random Forest, Decision Trees, and Gradient Boosting Regressor.
   - Hyperparameter tuning using grid search with TrainValidationSplit.
3. **Evaluation**:
   - Metrics: RMSE and SMAPE.
   - Insights from daily, weekly, and resampled trends.
4. **Prediction Back-Transformation**:
   - Reconstructed the Adjusted Close price from predicted price differences.

## Results
- Linear Regression and Random Forest models showed strong performance in capturing short-term trends.
- Decision Trees and Gradient Boosting provided varied accuracy, highlighting the complexity of longer-term forecasts.
- Visualizations confirmed the models’ effectiveness in predicting stock prices.

## Key Insights
- Short-term trends were effectively captured, providing value for day-to-day trading.
- Long-term trends offered insights for strategic investments.

## Technologies Used
- **Big Data Tools**: Apache Spark for scalable data processing.
- **Libraries**: PySpark, scikit-learn.
- **Visualization**: Matplotlib and Seaborn.

## References
1. Yahoo Finance API.
2. Federal Reserve Economic Data (VIXCLS and BAMLH0A0HYM2).
3. Apache Spark: A Unified Engine for Big Data Processing.

## Contributors
- Likhith Kolli
- Sahil Gauba
- Hemanth Chowdary
