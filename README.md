# Technical_Indicators

The Moving Averages and Candlestick Plotting Package provides a collection of technical indicators commonly used in financial analysis. 
This package aims to make it easy for traders and analysts by offering a set of tools for analyzing time series data, which include Simple Moving Average (SMA), 
Exponential Moving Average (EMA), Relative Strength Index (RSI), Autoregressive Moving Average (ARMA) models, and candlestick plotting.

## Design
The package consists of Two classes and Five Functions. Existing libraries like NumPy, pandas, and Matplotlib are used for data manipulation and visualization.

## Class: Moving_Averages
- The `simple_moving_average` and `exponential_moving_average` classes calculate the corresponding moving averages

`simple_moving_average` calculated using the below:
![image](https://user-images.githubusercontent.com/67727487/233747226-c0fc395f-8b75-471b-9fa4-435afaee0540.png)

`exponential_moving_average` calculated using the below:
![image](https://user-images.githubusercontent.com/67727487/233747308-3573010e-bcc6-4232-a1d7-32b9e16faa0e.png)

- The `relative_strength_index` class calculates the RSI values
- The `autoregressive_moving_average` class fits an ARMA model to the given data

## Class: CandlestickPlot
- The `candlestick_plot` class defines functions for generating candlestick plots


Each class has a method that accepts historical price data and returns the corresponding indicator values.

## Usage
To use the package, users can first install it using pip. They can then import the classes they need from the package and create an instance of the desired class. They can then call the method of the instance to calculate the corresponding indicator values.

## Discussion
Compared to similar libraries in Python, this package provides a more comprehensive set of tools for financial analysis. It is also designed to be user-friendly and easy to use, making it accessible to both novice and advanced users. One possible improvement to the package could be to include additional technical indicators commonly used in financial analysis to overcome the large dataset problem. However, the current set of indicators should be sufficient for most use cases.

## References
- [NumPy](http://www.numpy.org)
- [pandas](https://pandas.pydata.org/)
- [Matplotlib](https://matplotlib.org/)
- [Statsmodels](https://www.statsmodels.org/stable/index.html)
