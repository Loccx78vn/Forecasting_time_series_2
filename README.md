# Forecasting_time_series_2:
In the chapter 1 - "**Forecasting_time_series**", I introduced about the definition of time series, about a lot of forecasting approaches to deal with planning tasks. Our aim is analyzing time series by using machine learning.

Certainly! In R, both `timetk` and `modeltime` are packages designed to facilitate time series analysis and forecasting. Here's a brief summary of each:

# In R:
In this chapter, I will present the tutorial of time series forecasting by package `modeltime` and the combination between packages `timetk` and `recipe`.

## `timetk`

- **Purpose**: `timetk` is used for time series data manipulation and visualization. It helps in handling and transforming time-based data to make it more accessible for analysis and forecasting.
- **Key Features**:
  - **Date/Time Parsing**: Easily convert and format dates and times.
  - **Feature Engineering**: Create time-based features (e.g., year, month, day, weekday) to use in models.
  - **Visualization**: Functions for plotting time series data, including plotting with `ggplot2` and creating interactive visualizations.
  - **Aggregation and Resampling**: Aggregate data at different time intervals and resample time series data for different frequencies.

## `modeltime`

- **Purpose**: `modeltime` is designed for forecasting with time series data. It integrates with the `tidymodels` framework, enabling users to build, tune, and evaluate time series forecasting models.
- **Key Features**:
  - **Model Building**: Provides functions to fit various forecasting models, including ARIMA, ETS, and machine learning models.
  - **Model Evaluation**: Tools for assessing model performance using cross-validation and other metrics.
  - **Model Ensembling**: Combine multiple models to improve forecasting accuracy.
  - **Integration**: Works seamlessly with `timetk` for time series data preparation and `parsnip` for model specification.

In summary, `timetk` is great for preparing and visualizing time series data, while `modeltime` is focused on the modeling and forecasting aspects, allowing you to build and evaluate time series models effectively.

# Conclusion:
I hope you can enjoy the pratice and hope you have a great day!!! See you soon in another future topic.
