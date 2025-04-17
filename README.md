# GARCH Modelling – Equity Index Return Analysis

This project investigates the use of GARCH(1,1) models for modelling the returns of several equity indices. The objective is to explore the suitability of GARCH models in capturing the volatility dynamics of equity return series using historical closing price data provided in `IndexClosingPrices.xlsx`.

## Objectives

- Apply GARCH(1,1) models to the return series of multiple equity indices
- Test for stationarity of return series using the Augmented Dickey-Fuller (ADF) test
- Evaluate model fit and interpret estimated GARCH parameters
- Provide written analysis in response to key interpretive questions

## Analysis Requirements

1. **Load the data**  
   Import and organize index closing prices from the provided Excel file.

2. **Generate return series**  
   Compute log returns for each equity index in the dataset.

3. **Visualize data**  
   Plot both price series and return series for each index to observe trends and volatility clustering.

4. **Stationarity testing**  
   Apply the Dickey-Fuller (ADF) test to each return series to determine if it is stationary.

5. **Fit GARCH(1,1) models**  
   Estimate the parameters of GARCH(1,1) models for all return series and report the results.

6. **Answer interpretive questions**  
   - Q1: For which, if any, of the indices does the GARCH(1,1) model look suitable? If not, why not?  
   - Q2: If the return at time *t* is zero (i.e., \( R_t = 0 \)), which index has the highest expected return at time *t+1*? Why?

## Deliverables

- A Python file containing all analysis steps and model fitting code
- The code should include:
  - Data loading
  - Return calculations
  - ADF test implementation
  - GARCH(1,1) model fitting
  - Answers to Q1 and Q2 (as comments or printed outputs)
- Visual output: plots of prices, returns, and volatility where appropriate

## Tools & Libraries

- Python 3.x
- pandas
- numpy
- matplotlib
- statsmodels
- arch (for GARCH model estimation)

## Notes

This analysis is based on historical data and is intended for academic purposes. Model performance and interpretation are evaluated in the context of financial time series theory and volatility modeling best practices.
