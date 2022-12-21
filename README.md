# Time-series-forescasting
Time series forecasting of fuel prices for different stations.
Price data of fuel stations. Those include prices from 19 fuel stations in Germany from 01/01 until 31/12/2021.

The data is structured as follows:

date: time stamp

station_uuid: Unique allocation of a fuel station

diesel: Diesel price of the corresponding fuel station (station_uuid) at given time (date) in €

e5: Super e5 Price of the corresponding fuel station (station_uuid) at given time (date) in €

e10: Super e10 Price of the corresponding fuel station (station_uuid) at given time (date) in €

dieselchange: 1, if Diesel price changed compared to last time, 0 otherwise

e5change: 1, if Super e5 price changed compared to last time, 0 otherwise

e10change: 1, if Super e10 price changed compared to last time, 0 otherwise

Task 1 Descriptive Analysis.

Task 2 Forecasting for 5 days on hourly resolution (01/01 – 05/01/2022) on how the prices on all 19 fuel stations will
develop. 

Task 3 This task addresses the comparability of all 19 fuel stations. The main goal is an algorithm-based classification of the stations into sensible clusters. 
