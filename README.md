# Time-series-Forecasting-using-ML-DL-and-classical-methods

# Time Series Forecasting on NIFTY Stocks

This repository contains an end-to-end forecasting pipeline for stock price time series from the NIFTY 50 universe.  
The project demonstrates classical statistical models, machine learning methods, and deep learning architectures for univariate financial time-series forecasting.

The pipeline is fully generic and works for any stock placed inside the `nifty/` folder.

---

## Project Overview

The workflow includes:

1. Data loading and preprocessing  
2. Exploratory time series analysis  
3. Classical forecasting models  
4. Machine learning models  
5. Deep learning models  
6. Model evaluation and comparison  

Each model can be applied to any chosen stock by specifying the file name.

---

## Data

The dataset should be placed inside the `nifty/` directory in the following CSV format:

- Date  
- VWAP  

The pipeline automatically parses dates and sets them as the index.
