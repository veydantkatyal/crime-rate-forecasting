## Overview

This project aims to predict future crime rates in Chicago using time series forecasting methods. The dataset consists of historical crime data, which is processed and fed into **Facebook Prophet**, a robust forecasting tool developed by Facebook. The model is used to forecast future crime rates based on past trends and seasonal patterns.

## Project Objective

- To analyze and forecast the crime rate in Chicago using historical crime data.
- To explore seasonal patterns, weekly trends, and potential anomalies in crime data.
- To implement **Facebook Prophet** for time series forecasting and visualize the results.

## Key Features

- **Data Preprocessing**: Cleaning and transforming raw crime data into a time-series format.
- **Exploratory Data Analysis (EDA)**: Visualization of crime trends over time, monthly/weekly trends, and outliers.
- **Facebook Prophet Forecasting**: Implementation of Prophet for predicting future crime rates.
- **Evaluation**: Model performance evaluation using metrics like Mean Absolute Error (MAE) and visualization of forecast vs. actual crime data.
- **Visualizations**: Trend plots, seasonality analysis, and forecast results.

## Dataset

The dataset used for this project contains historical crime data from the City of Chicago. You can access the dataset from [Chicago Data Portal](https://data.cityofchicago.org/).

### Columns of Interest:

- `Date`: The date of the crime incident.
- `Primary Type`: The type of crime (e.g., theft, assault, robbery).
- `Description`: Detailed description of the crime.
- `Location Description`: The location where the crime occurred.
- `Year`: The year of the incident.
- `Arrest`: Whether an arrest was made or not.

## System Requirements

To run this project, you'll need the following:

- **Python** 3.6 or higher
- **Facebook Prophet** (v0.7 or higher)
- **pandas** (v1.1 or higher)
- **matplotlib** (v3.3 or higher)
- **seaborn** (v0.11 or higher)

You can install the required packages using the following command:

```bash
pip install pandas matplotlib seaborn prophet



