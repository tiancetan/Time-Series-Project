# Time-Series-Project
Introduction Data description
The Zillow dataset (modified) recorded Feb 2008- Dec 2015 monthly median sold price for housing in California, Feb 2008-Dec 2016 monthly median mortgage rate, and Feb 2008-Dec 2016 monthly unemployment rate.
Models used
1. ARIMA
Autoregressive Integrated Moving Average Model
2. SARIMA
Seasonal Autoregressive Integrated Moving Average
3. ETS
The ETS models are a family of time series models consisting of a level component, a trend component (T), a seasonal component (S), and an error term (E)
4. Multivariate
Multivariate time series has more than one time-dependent variable
5. LSTM
Long short-term memory - a type of recurrent neural network
6. Prophet
An open source software released by Facebook's Core Data Science team


## Final Result
We set the basic prophet model as the best one because adding seasonality and holiday does not improve the model performance. Though the actual prices always exceed the predicted one, the difference in the gap makes it a decent prediction. The final model on the test dataset has a score of RMSE 8919 and MAPE 0.0129.

<img width="523" alt="Screen Shot 2021-04-14 at 12 31 20 AM" src="https://user-images.githubusercontent.com/69778068/114659180-bcc6e900-9cb8-11eb-944d-d35068f5e793.png">
