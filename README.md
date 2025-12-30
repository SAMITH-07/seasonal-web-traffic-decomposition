# Seasonal Decomposition of Web Traffic

## Overview
This project analyzes daily website traffic using seasonal decomposition techniques to understand underlying trends, seasonal patterns, and irregular fluctuations in web traffic data.

Since no dataset was provided, a synthetic daily web traffic dataset was generated to demonstrate the complete analysis workflow.

---

## Technologies Used
- Python  
- pandas  
- statsmodels  
- matplotlib  

---

## Project Objective
The main objective of this project is to:
- Decompose web traffic data into trend, seasonality, and residual components  
- Understand recurring user behavior patterns  
- Identify potential anomalies such as sudden spikes or drops in traffic  

---

## Dataset Description
- Daily website visit counts for one year  
- Includes weekly seasonal patterns  
- Random noise added to simulate real-world behavior  
- Missing dates introduced intentionally and handled through interpolation  

---

## Data Preparation
The following steps were performed:
- Generated synthetic daily traffic data  
- Introduced missing dates artificially  
- Reindexed the time series to daily frequency  
- Filled missing values using linear interpolation  

This ensured a clean and continuous time series for analysis.

---

## Methodology
Two seasonal decomposition methods were applied:

### 1. Additive Decomposition
- Assumes seasonal effects remain constant over time  
- Useful when variations do not depend on traffic volume  

### 2. Multiplicative Decomposition
- Assumes seasonal effects change proportionally with traffic volume  
- Useful when higher traffic intensifies seasonal patterns  

---

## Visualizations
For both decomposition methods, the following components were visualized:
- Original web traffic  
- Trend component  
- Seasonal component  
- Residual component  

These plots help in interpreting traffic behavior and detecting irregular patterns.

---

## Key Observations
- A consistent weekly seasonal pattern is visible, indicating regular user behavior  
- The trend component shows gradual changes in overall traffic  
- The multiplicative model highlights stronger seasonal effects during high-traffic periods  
- Residuals help identify potential anomalies  

---

## Conclusion
Seasonal decomposition effectively breaks down web traffic data into meaningful components. This analysis helps in understanding user behavior, identifying seasonal peaks, and detecting unusual patterns, which can support better forecasting and decision-making.

---

## Demo
Google Colab Notebook:  
https://colab.research.google.com/drive/1cdUHjAidNmrDHMAjxSMQk_rEOGl1bZEz?usp=sharing

---

## Notes
- Synthetic data was used due to the absence of a provided dataset  
- This project is intended for educational and demonstration purposes  
