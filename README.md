## GARCH Time Series Forecasting for INR/EUR Exchange Rate
This project analyzes the INR/EUR exchange rate data between the time periods of January 2002 and November 2024. It visualizes the price and returns of the INR per EUR and then uses the GARCH(1,1) model for time series forecasting INR/EUR exchange rate. 

### Dataset & Usage
I downloaded the data from the European Central Bank's website for the period of January 2002 and November 2024. I've restricted myself to a monthly frequency, although these days it's possible to have a much higher frequency (daily or hourly, for instance) for time series data. I've also added the dataset as a CSV file.

### Software and Packages Used 
This project is entirely done on R. You would need the following packages: 
1. Tidyverse (Data manipulation and visualization)
2. Forecast (Time series forecasting)
3. Rugarch  (GARCH modeling)

### Notes 
1. I've used a Student's T-distribution rather than a standard normal distribution as it better accounts for fatter tails.
2. In the future, I would like to compare this data with volume of trade and check for correlations between trade balance fluctutaions ans exchange rate volatility. 
3. I'm new to github so I'm not sure if I'm doing this quite right.
