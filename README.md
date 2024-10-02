# Bike Sharing Assignment for UpGrad

## Problem Statement

Bike-sharing systems provide bikes for short-term use, either for free or at a fee. Typically, users pick up a bike from a computer-controlled "dock" by entering payment information and can return it to another dock in the same system.

A US-based bike-sharing provider, **BoomBikes**, has experienced a sharp revenue drop due to the ongoing COVID-19 pandemic. The company is struggling to sustain itself in the current market conditions and is seeking a strategic plan to boost revenue once the lockdown ends and the economy recovers.

To prepare for post-lockdown demand, BoomBikes wants to understand the factors influencing bike rentals. By doing so, they aim to meet customer needs, outperform competitors, and achieve significant profits.

To achieve this, BoomBikes has hired a consulting firm to analyze factors affecting bike demand in the American market. They want to know:

- **Which factors significantly affect bike demand?**
- **How well do these factors explain variations in demand?**

BoomBikes has collected a large dataset on daily bike demand, influenced by weather conditions and user behaviors. Your task is to model this demand using the available independent variables. The goal is to provide management with insights on how bike demand changes based on different features, helping them to optimize their strategy.

## Business Goal

Build a model to predict the demand for shared bikes using the provided independent variables. This model will help BoomBikes’ management understand how demand changes based on different factors, allowing them to adjust their strategy. The model will also offer insights into demand dynamics in new markets.

## General Information

BoomBikes aims to:

- Identify significant variables for predicting bike demand.
- Understand how well these variables explain the variation in demand.

## Conclusion

The linear regression model was successful in predicting bike demand with an **R² score of over 80%**.

## Final Equation

```plaintext
cnt = 0.174 + (0.234 * yr) - (0.056 * holiday) + (0.047 * workingday) + (0.473 * temp) 
      - (0.156 * windspeed) - (0.06 * season_Spring) + (0.043 * season_Summer) 
      + (0.08 * season_Winter) - (0.039 * mnth_Jan) - (0.048 * mnth_Jul) 
      + (0.075 * mnth_Sep) + (0.058 * weekday_Sat) - (0.292 * weathersit_Light Rain or Light Snow) 
      - (0.083 * weathersit_Misty and Cloudy)
```
## Technologies Used

NumPy: For numerical calculations and array operations.
Pandas: For data manipulation and analysis.
Matplotlib: For data visualization.
Seaborn: For enhanced statistical visualizations.
scikit-learn: For machine learning model creation, feature selection, data preprocessing, and model evaluation.
Statsmodels: For statistical modeling, regression, and multicollinearity analysis.
Warnings: To manage warning messages during the process.
These libraries are essential for data analysis, feature selection, building the regression model, and evaluating its performance. They help streamline the process of creating an accurate and effective multiple linear regression model for predicting bike demand.

## Created by [ersatyamsingh1990] for Upgrad
