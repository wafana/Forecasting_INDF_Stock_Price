# Time Series Forecasting: Predicting Stock Price of INDF

## Business Problem Understanding
### Background
PT Indofood Sukses Makmur Tbk. (ticker: INDF.JK) is a prominent consumer goods company listed on the Indonesia Stock Exchange (IDX). Given Indonesia’s growing economy and the significance of the consumer goods sector, many investors and market analysts closely monitor INDF’s stock price movements. Accurately predicting the future price of INDF.JK is essential for various stakeholders—ranging from retail investors aiming to optimize their portfolios to institutional investors seeking to manage risk and allocate assets effectively.
However, forecasting a stock price involves navigating a complex landscape influenced by numerous factors, including but not limited to: market sentiment, macroeconomic indicators, competitive dynamics, and company-specific events. Furthermore, price fluctuations can happen rapidly, reflecting global market conditions and investor behavior. This complexity highlights the need for a robust forecasting model capable of capturing the underlying trends and seasonality in the time series data.

### Problem Statement
One of the most pressing challenges in financial markets is developing an accurate method for forecasting future stock prices. The dynamic nature of stock markets, shaped by both intrinsic company performance and extrinsic economic conditions, makes prediction tasks notably difficult. For investors focused on INDF.JK, an inaccurate forecast can translate into suboptimal decisions, potential financial losses, and missed opportunities. Consequently, establishing a reliable approach to time series forecasting is critical to mitigate risks and improve overall decision-making quality.

### Goals
The primary objective of this analysis is to design and implement a time series forecasting model that can predict the future price of INDF.JK with a high degree of accuracy. By doing so, we aim to:

- Assist individual and institutional investors in making better-informed trading or investment decisions.
- Provide an analytical tool for portfolio managers to optimize asset allocation and manage risk effectively.
- Offer insights into market patterns and trends, contributing to a deeper understanding of the stock’s behavior in varying market conditions.
**Analytical Approach**
To achieve these goals, the following steps will be undertaken:

### Data Collection and Exploration
Gather historical stock price data for INDF.JK, including daily closing prices, trading volumes, and other relevant features using python web scraping.

Model Development
- Utilize various time series forecasting techniques (e.g., ARIMA, SARIMA, and Prophet).
- Perform hyperparameter tuning and model selection to identify the best-performing approach.

Validation and Testing
- Split the dataset into training, validation, and test sets to evaluate model performance objectively.
- Compare forecast accuracy across different models to ensure that the final model aligns with business needs.

Metric Evaluation
For stock price forecasting, the following metrics will be used to evaluate model performance:
- RMSE (Root Mean Squared Error): Provides a measure of the magnitude of errors by taking the square root of the average squared differences between the predicted and actual stock prices.
- MAE (Mean Absolute Error): Reflects the average absolute deviation of the model’s predictions from the actual prices, offering an intuitive measure of forecast accuracy.
- MAPE (Mean Absolute Percentage Error): Expresses prediction errors as a percentage of actual values, making it easier to compare forecasting performance across different scales.
Lower values of RMSE, MAE, and MAPE indicate a more accurate model for predicting INDF.JK stock prices. Because these metrics capture how close the predictions are to the actual prices, they are most relevant for assessing model performance in terms of stock price prediction.
