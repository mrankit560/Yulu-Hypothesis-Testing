
# Yulu Hypothesis Testing

## About Yulu

Yulu is India's leading micro-mobility service provider, aiming to resolve traffic congestion issues and promote sustainable commuting options. Yulu offers a user-friendly mobile app for accessing its fleet of shared, solo, and electric vehicles, strategically located across various zones for seamless first and last-mile connectivity.

Despite its innovative approach, Yulu has observed significant revenue dips. To address this, a detailed analysis is required to understand the factors influencing the demand for shared electric cycles in the Indian market.

## Project Objective

The primary goal of this analysis is to identify variables that significantly predict the demand for shared electric cycles and understand the extent of their impact. This involves exploring various factors such as seasonality, weather conditions, and operational days, and how they correlate with the usage patterns of Yulu's services.

## Dataset Overview

The analysis is based on data captured in `yulu_data.csv`, encompassing various factors including:

- **datetime:** Date and time
- **season:** Season (1: spring, 2: summer, 3: fall, 4: winter)
- **holiday:** Indicates if the day is a holiday
- **workingday:** Identifies if the day is a working day
- **weather:** Categorizes weather conditions
- **temp:** Temperature in Celsius
- **atemp:** 'Feels like' temperature in Celsius
- **humidity:** Humidity percentage
- **windspeed:** Wind speed
- **casual:** Count of casual users
- **registered:** Count of registered users
- **count:** Total count of bikes rented

## Analysis Methodology

The study employs various statistical tests and analytical techniques to explore the data, including:

- Bi-variate analysis
- 2-sample t-test
- ANOVA
- Chi-square test

These methods help in understanding the relationship between the dependent variable (bike rentals) and several independent variables such as working days, weather, and seasons.

## Key Findings

*Analysis of the `Yulu Hypothesis.ipynb` notebook reveals significant insights into the factors affecting electric cycle demand. The README will briefly highlight the major conclusions drawn from hypothesis testing, such as the impact of working days, seasonality, and weather conditions on bike rental patterns.*

## How to Use This Repository

- `Yulu Hypothesis.ipynb`: Jupyter notebook containing detailed data analysis, including hypothesis testing and statistical modeling.
- `yulu_data.csv`: Dataset used for the analysis.

The repository is designed to offer insights into Yulu's shared electric cycle demand and support strategic decisions to enhance service utilization.
