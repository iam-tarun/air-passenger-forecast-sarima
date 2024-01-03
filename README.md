# air-passenger-forecast-sarima

This project leverages the Seasonal Autoregressive Integrated Moving Average (SARIMA) model to forecast air passenger data. By employing time series analysis techniques, My aim is to predict future air travel demand, providing valuable insights for airline industry planning and optimization. The project involves data preprocessing, model training, and evaluation, showcasing the power of SARIMA in capturing seasonality and trends within the airline passenger dataset.

## Table of Contents

- [Project Overview](#project-overview)
- [Dataset](#dataset)
- [Methods and Techniques](#methods-and-techniques)
- [Results](#results)

## Project Overview

This project focuses on utilizing the SARIMA (Seasonal Autoregressive Integrated Moving Average) model to forecast air passenger data. The primary objective is to predict future trends in air travel demand based on historical patterns. By analyzing the seasonality and underlying patterns in the data, the project aims to provide accurate and actionable predictions for airline industry stakeholders.

**Objectives:**

1. Develop a robust SARIMA forecasting model for air passenger data.
2. Explore and understand the seasonality and trends within the dataset.
3. Train the model on historical data to predict future air travel demand.
4. Evaluate the model's performance using appropriate metrics.
5. Provide insights and visualizations to aid in decision-making for airline industry planning and resource allocation.

**Context:**

The aviation industry relies heavily on accurate predictions of passenger demand to optimize operations, manage resources efficiently, and enhance overall customer experience. By leveraging SARIMA, a powerful time series forecasting tool, this project aims to contribute valuable insights to the industry, helping stakeholders make informed decisions based on data-driven forecasts.

---

## Dataset

The Air Passengers dataset used in this project was sourced from the "International Airline Passengers" dataset.

- **Title:** International Airline Passengers dataset
- **Author:** Box, G. E. P., Jenkins, G. M., & Reinsel, G. C.
- **Source:** Box, G. E. P., Jenkins, G. M., & Reinsel, G. C. (1976). Time Series Analysis: Forecasting and Control. San Francisco: Holden-Day.

[Link to the dataset source](https://datamarket.com/data/set/22u3/international-airline-passengers-monthly-totals-in-thousands-jan-49-dec-60)

## Methods and Techniques

1. **Data Preprocessing:**
   - Address missing values through interpolation.
   - Convert date-related columns to datetime format.
   - Conduct exploratory data analysis (EDA) for insights.

2. **Feature Engineering:**
   - Generate lag features to capture historical air passenger trends.
   - Use seasonal decomposition to identify trend, seasonality, and residuals.

3. **Modeling Approach - SARIMA:**
   - Apply SARIMA for autoregressive and seasonal modeling.
   - Experiment with parameter tuning for optimization.
   - Split data into training and testing sets for evaluation.

4. **Evaluation:**
   - Assess model performance using metrics like MSE and MAE.
   - Visualize time series plots and predicted vs. actual comparisons.

5. **Optimization and Fine-Tuning:**
   - Conduct grid search for SARIMA hyperparameter exploration.
   - Fine-tune hyperparameters based on grid search results.

By employing these techniques, the project aims to build an accurate SARIMA model for forecasting air passenger demand.

## Results


