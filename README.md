# Daily Forecast

## Overview
Applying varied statistical models to predict daily returns of US Equities, considering the applicability of each model to different assets.

## Resources And Skills Involved
gpflow, tensorflow, statsmodels, statistics, sklearn, numpy.

## Data Sources 

Kaggle US Equities Data (1992-2019)     
Kaggle US reported financial Data (2010-2020)       

https://www.kaggle.com/finnhub/reported-financials      
https://www.kaggle.com/finnhub/end-of-day-us-market-data-survivorship-bias-free     

The price data is survivorship bias free with dividend adjustments 

## Project Stages

### Stage 1: Initial Research

Different statistical models will be reviewed, and prototypes will be generated through Jupyter Notebooks. The main point of this stage is to have the models ready to create a python class once the infrastructure team enables the funcionalities for a full-blown analysis of the models.

### Stage 2: Model Development With Python Classes

The models will then be written into a homogeneous environment that can run smoothly with the functionalities developed by the other research teams. This will allow for a deeper analysis, improving the quality of our data sources and improving the portability of our models.

### Stage 3: Testing Of Our Models

The Algosoc backtester will be used to test the models developed. Conclusions will be drawn to relate performance of each models to different assets, timeframes or other factors.

## Models

### Gaussian Processes

A Gaussian process is a supervised learning method that assigns multvaritate normal distributions to each variable within a random variable collection. These models are controlled by covariance functions, and must be tailored to address specific prediction tasks.

### Auto-regressive integrated moving average (ARIMA)

An ARIMA model are fitted to time series to better understand the data or predict future points in the series. ARIMA models are applied whenever the condition of statistical stationarity is not met by the dataset. As an auto-regressive model, the variables of interest are regressed on their previous values, where the regression error is a linear combination of error terms whose values occurred at various times in the past.

## Literature Review

### Gaussian Processes

[1] MCMC for Variationally Sparse Gaussian Processes J Hensman, A G de G Matthews, M Filippone, Z Ghahramani Advances in Neural Information Processing Systems, 1639-1647, 2015.

[2] The variational Gaussian approximation revisited M Opper, C Archambeau Neural computation 21 (3), 786-792, 2009.

[3] Scalable Variational Gaussian Process Classification J Hensman, A G de G Matthews, Z Ghahramani Proceedings of AISTATS 18, 2015.

[4] Variational Learning of Inducing Variables in Sparse Gaussian Processes. M Titsias Proceedings of AISTATS 12, 2009.

### ARIMA

[1] Asteriou, Dimitros; Hall, Stephen G. (2011). "ARIMA Models and the Box–Jenkins Methodology". Applied Econometrics (Second ed.). Palgrave MacMillan. pp. 265–286. ISBN 978-0-230-27182-1.

[2] Mills, Terence C. (1990). Time Series Techniques for Economists. Cambridge University Press. ISBN 978-0-521-34339-8.

[3] Percival, Donald B.; Walden, Andrew T. (1993). Spectral Analysis for Physical Applications. Cambridge University Press. ISBN 978-0-521-35532-2.
