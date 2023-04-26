# Time-Series
Time series analysis of passenger count data. 

* It imports the necessary libraries such as pandas, numpy, and matplotlib. Converts the Datetime column in both datasets to datetime format using the pd.to_datetime() function.

* Creates additional columns in the datasets for the year, month, day, and hour using the Datetime column.

* Creates four time series plots to show passenger count trends at the hourly, daily, weekly, and monthly levels.

* Splits the Train dataset into two subsets, one for training and one for validation. It uses the Holt-Winters method to create a linear forecast for the validation dataset and 
calculates the root mean square error (RMSE) for the forecast. 

* Uses the ARIMA model with parameter tuning to remove trend and seasonality from the data, and then plots the rolling mean and standard deviation of the dataset.
