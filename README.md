# CrimeTrendAnalysis2020
# Cleaning and Analyzing Crime Data

This repository contains the work of Group Number 7 for the project in IE6400 Foundations of Data Analytics Engineering. The project focuses on cleaning, analyzing, and forecasting crime data to understand trends and patterns, which could aid in better law enforcement and policy-making.

## Team Members
- Kaajal Shah
- Khushboo Narendra Galrani
- Naga Venkata Sai Sreeya Galla
- Soumitra Rajeev Bhagdikar
- Vaishnavi Gaikwad

## Project Overview

The goal of this project was to meticulously clean the provided crime data, perform exploratory data analysis, and apply time series forecasting to predict future crime rates. The dataset spans from the year 2020 to the present, covering various crime incidents reported across different regions.

### Part 1: Data Cleaning
The data cleaning process involved:
- Identifying and handling missing data.
- Resolving duplicate entries to ensure data integrity.
- Converting data types for accurate analysis (e.g., converting dates and times to appropriate formats).
- Detecting and managing outliers using the Interquartile Range (IQR) method.

### Part 2: Exploratory Data Analysis (EDA)
The EDA phase focused on:
- Visualizing overall crime trends over the years.
- Analyzing seasonal patterns and identifying months with higher crime rates.
- Examining the most common types of crimes and their trends.
- Investigating differences in crime rates between different regions.
- Exploring correlations between economic factors and crime rates.

### Part 3: Time Series Forecasting
For forecasting future crime rates:
- A new column "No of Crime" was introduced to quantify daily crime rates.
- An ARIMA model was implemented to forecast crime rates for the upcoming months.
- The model's accuracy was assessed using Root Mean Square Error (RMSE).

## Files in the Repository
- `DATA.csv`: The original dataset used for analysis.
- `FDA_Project_1_Final.ipynb`: Jupyter notebook containing all the scripts for data cleaning, EDA, and forecasting.
- `group_7_report.pdf`: Comprehensive project report detailing each step of the project and findings.

## Conclusions
This project highlights the significance of data-driven approaches in understanding crime dynamics. The insights derived from the analysis can help in shaping effective crime prevention strategies and in the allocation of law enforcement resources.

## How to Use
1. Clone this repository to your local machine.
2. Ensure you have Jupyter Notebook installed, or use any platform that supports `.ipynb` files.
3. Run the `FDA_Project_1_Final.ipynb` notebook to see the analysis and forecasting steps.


