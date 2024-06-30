# CPI and BER Data Analysis: Forecasting and Evaluating Inflation Metrics

## Overview

This project aims to analyze the Consumer Price Index (CPI) and Break-even Rate (BER) data over the past decade. By applying time series forecasting techniques, we predict future CPI values and evaluate the model's performance using mean squared prediction error (MSPE). The analysis provides insights into inflation trends and helps in understanding the relationship between CPI and BER.

![Project Overview](https://github.com/Youssra1999/Forecasting-and-Evaluating-Inflation-Metrics/blob/main/CPI%20and%20BER%20Data%20Analysis%20Forecasting%20and%20Evaluating%20Inflation%20Metrics.png)

## Table of Contents
- [Overview](#overview)
- [Data Description](#data-description)
- [Methodology](#methodology)
- [Results](#results)
- [Conclusion](#conclusion)
- [How to Run the Project](#how-to-run-the-project)
- [Acknowledgments](#acknowledgments)

## Data Description

The dataset includes daily observations for CPI and PriceStats over a decade. The primary columns are:
- `date`: The date of the observation.
- `PriceStats`: The PriceStats index value.
- `CPI`: The Consumer Price Index value.

## Methodology

1. **Exploratory Data Analysis (EDA)**: Initial analysis to understand the distribution and trends in the data.
2. **Data Preprocessing**: Includes date conversion, removing duplicates, splitting the data into training and testing sets, and log transformation of CPI values.
3. **Data Visualization**: Visual representation of CPI trends and detrending analysis to isolate underlying patterns.
4. **Modeling**: Application of ARIMA and SARIMAX models to predict CPI values.
5. **Evaluation**: Performance evaluation using mean squared prediction error (MSPE).

## Results

- **Trend Analysis**: Identified an overall upward trend in CPI values, with short-term variations and periods of stability.
- **Model Performance**: The AR(2) model provided accurate predictions with a low MSPE. Incorporating BER as an exogenous variable improved the model's accuracy.
- **Detrended Data Analysis**: Successfully isolated residuals to understand underlying patterns and fluctuations in CPI data.

## Conclusion

This study demonstrates the effective application of time series forecasting techniques to predict CPI values. By incorporating BER as an exogenous variable and adding Moving Average terms, the model's predictive accuracy was significantly improved. These findings contribute to a better understanding of inflation metrics and their implications for economic planning and policy-making.

## How to Run the Project

1. **Clone the repository**:
    ```sh
    git clone https://github.com/yourusername/cpi-ber-analysis.git
    ```
2. **Install required packages**:
    ```sh
    pip install -r requirements.txt
    ```
3. **Run the analysis**:
    Open the Jupyter notebook `CPI_BER_Analysis.ipynb` and run the cells sequentially to reproduce the analysis.

## Acknowledgments

I would like to acknowledge the Bureau of Labor Statistics for providing the CPI data and other relevant resources that were instrumental in this study. Their contributions have been invaluable to the success of this research.

---

For more details, please refer to the full [project report](https://github.com/yourusername/cpi-ber-analysis/blob/main/CPI_and_BER_Data_Analysis.pdf).

Feel free to connect with me on [LinkedIn](https://www.linkedin.com/in/yourlinkedinprofile) for any questions or discussions related to this project.
