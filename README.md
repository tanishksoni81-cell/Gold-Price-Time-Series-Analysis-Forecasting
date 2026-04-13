# Gold-Price-Time-Series-Analysis-Forecasting
This project focuses on analyzing historical gold price data and identifying patterns over time. Using time series techniques, it aims to understand trends, volatility, and make future predictions.

Dataset

Monthly gold price data
Time period: 1950 to 2021
Features: Date, Price

Tools & Technologies

Python
Pandas & NumPy
Matplotlib & Seaborn
Statsmodels

Project Workflow

1. Data Preparation
Loaded dataset
Converted date column to datetime
Set date as index for time series analysis
2. Exploratory Data Analysis (EDA)
Visualized long-term price trends
Checked statistical summary (mean, std, etc.)
Analyzed yearly distribution using boxen plots
Detected monthly patterns using month plots
3. Time-Based Analysis
Aggregated data yearly, quarterly, and decade-wise
Calculated Mean and Standard Deviation
Computed Coefficient of Variation (CV%) to measure volatility
4. Model Building
Applied Exponential Smoothing
Included trend and seasonal components
Tuned smoothing parameters
5. Forecasting & Visualization
Predicted future gold prices
Compared actual vs forecast values
Visualized confidence intervals

Key Insights

Gold prices show a consistent upward trend over time
Some periods exhibit high volatility (high CV%)
Seasonal patterns are not very strong
Long-term predictions carry higher uncertainty

Conclusion

This project demonstrates how time series analysis can be used to:

Understand long-term trends in financial data
Measure risk and stability using statistical techniques
Support smarter investment and business decisions

Exponential Smoothing proved effective in capturing trends, but accuracy can be further improved using advanced models like ARIMA or Prophet.
