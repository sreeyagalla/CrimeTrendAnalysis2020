# CrimeTrendAnalysis2020
# Cleaning and Analyzing Crime Data

This repository contains the work of Group Number 7 for the project in IE6400 Foundations of Data Analytics Engineering. The project focuses on cleaning, analyzing, and forecasting crime data to understand trends and patterns, which could aid in better law enforcement and policy-making.

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

### Visualizations
-Overall Crime Trends from 2020 to the Present Year
![image](https://github.com/sreeyagalla/CrimeTrendAnalysis2020/assets/163912617/498c2c47-bc7e-4614-8a28-3b281f26e7d5)

-Seasonal Patterns in Crime Data
![image](https://github.com/sreeyagalla/CrimeTrendAnalysis2020/assets/163912617/7f86a27f-9270-4112-930d-eec7492eefb1)

-Most common type of crime
![image](https://github.com/sreeyagalla/CrimeTrendAnalysis2020/assets/163912617/8ffc656c-8fc3-4c6d-86a0-3e7b0c7437de)

-Analyzing most common crime trend over time
![image](https://github.com/sreeyagalla/CrimeTrendAnalysis2020/assets/163912617/408f6100-1bf3-45b4-9d66-4fde80391daa)

-Crime Rates Between Regions or Cities
![image](https://github.com/sreeyagalla/CrimeTrendAnalysis2020/assets/163912617/45e84339-49d0-4f91-b952-c8939149a910)

-Correlations Between Economic Factors and Crime Rates
![image](https://github.com/sreeyagalla/CrimeTrendAnalysis2020/assets/163912617/be1254a6-ba44-49cd-95bb-ea4476d6d829)

-Relationship Between the Day of the Week and the Frequency of Certain Types of Crimes
![image](https://github.com/sreeyagalla/CrimeTrendAnalysis2020/assets/163912617/e67f3f5e-bfae-4bc7-bae5-37cc1b969bbd)

-Investigate any Impact of Major Events or Policy Changes on Crime Rates
![image](https://github.com/sreeyagalla/CrimeTrendAnalysis2020/assets/163912617/52eb7267-6104-4bd7-87a1-c08b91641312)

![image](https://github.com/sreeyagalla/CrimeTrendAnalysis2020/assets/163912617/2218be0d-73dc-4b52-8708-592e8096b26f)

![image](https://github.com/sreeyagalla/CrimeTrendAnalysis2020/assets/163912617/d6b5123d-fb79-407f-8132-1309c7bfcfc5)

-Outliers and Anomalies in the Dataset
![image](https://github.com/sreeyagalla/CrimeTrendAnalysis2020/assets/163912617/02bbe9c2-e225-46e9-94b4-8449c810caa5)

![image](https://github.com/sreeyagalla/CrimeTrendAnalysis2020/assets/163912617/1d048e72-f84f-4f24-a808-0f4f6749636b)

-Identifying pattern or correlation between Demographic factors and Types of crime
![image](https://github.com/sreeyagalla/CrimeTrendAnalysis2020/assets/163912617/b60794b6-026a-4ba2-98da-db0e4952b089)

- Identifying Future Crime Trends
![image](https://github.com/sreeyagalla/CrimeTrendAnalysis2020/assets/163912617/41e34297-ea45-4ce7-81b1-626ea4815c00)

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


