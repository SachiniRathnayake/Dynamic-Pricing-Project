# Dynamic Pricing Project

This project implements a data-driven dynamic pricing strategy using Python. It involves exploratory data analysis, dynamic pricing implementation, and training a machine learning model to predict ride costs.

## Table of Contents
- [Introduction](#introduction)
- [Dataset](#dataset)
- [Exploratory Data Analysis (EDA)](#exploratory-data-analysis-eda)
- [Dynamic Pricing Strategy](#dynamic-pricing-strategy)
- [Machine Learning Model](#machine-learning-model)
- [Results](#results)

## Introduction
Dynamic pricing is a strategy where prices are adjusted based on various factors in real time. This project demonstrates how to use machine learning and data analysis to implement a dynamic pricing model that optimizes revenue by adjusting ride prices based on demand and supply dynamics.

## Dataset
The dataset used in this project contains information about rides, including the number of riders and drivers, location, customer loyalty status, past rides, average ratings, time of booking, vehicle type, expected ride duration, and historical ride cost.

## Exploratory Data Analysis (EDA)
- Descriptive statistics
- Scatter plot of expected ride duration vs. historical cost of ride

  ![Expected ride duration vs  Historical Cost of ride](https://github.com/SachiniRathnayake/Dynamic-Pricing-Project/assets/144448061/f0fdccc8-f812-420b-be6c-c34896a61e32)

- Box plot of historical cost of ride by vehicle type

  ![Historical Cost of ride Distribution by Vehicle Type](https://github.com/SachiniRathnayake/Dynamic-Pricing-Project/assets/144448061/f861b2f1-917f-4e41-86d8-df79c878d2bd)

- Box plot of historical cost of ride by Tiime of Booking

  ![Historical Cost of ride Distribution by Time of Booking](https://github.com/SachiniRathnayake/Dynamic-Pricing-Project/assets/144448061/f7e8dcaf-936e-4474-bdee-ae174c2f6cd6)

- Correlation matrix heatmap

  ![Correlation Matrix](https://github.com/SachiniRathnayake/Dynamic-Pricing-Project/assets/144448061/57c3f5fd-a396-49d6-96dd-02f4c828c112)


## Dynamic Pricing Strategy
The dynamic pricing strategy adjusts ride costs based on demand and supply levels. The demand and supply multipliers are calculated using percentiles, and the adjusted ride cost is determined by multiplying the historical cost by these multipliers.

## Machine Learning Model
A Random Forest Regressor is used to predict ride costs based on the number of riders, number of drivers, vehicle type, and expected ride duration.

## Results
- Profitability analysis using a donut chart

![Profitability of Rides (Dynamic Pricing vs  Historical Pricing)](https://github.com/SachiniRathnayake/Dynamic-Pricing-Project/assets/144448061/c669a1ba-f222-48ef-9206-fb5f647a2a28)

- Scatter plot of actual vs. predicted ride costs

![Actual vs Predicted Values](https://github.com/SachiniRathnayake/Dynamic-Pricing-Project/assets/144448061/2b412145-0f78-4368-ae83-32d74f5f0400)
