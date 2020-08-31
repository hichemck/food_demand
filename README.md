# Food Demand Forecasting

Demand forecasting has taken a crucial role in modern businesses. Especially 
a food delivery service has to deal with perishable raw material and to 
ensure having the right stock quantity at any time. 

For my final project in the Spiced Bootcamp I chose to tackle these challenges with different methods.

The challenge has been proposed by Analytics Vidhya which is a plattform for 
data science challenges.

[link to the challenge](https://datahack.analyticsvidhya.com/contest/genpact-machine-learning-hackathon-1/)

# Task

The client has 77 operating centers (located in different cities) and delivers
51 meals. 
The provided data set consists in orders quantities for different meals in 
different centers during 145 weeks. My job is to predict orders quantities 
for the 10 subsequent weeks.
Part of the challenge is that the the combinations meal/center change for each 
week and some combination occure less than others. Further, there
are combinations in the test set that are not available in the train set.


# Work breakdown

- Data exploration
- Data wrangling 
- Prediction benchmark
- Run different regression models: Linear - Poisson 
- Add lagged values as new feature and perform recursive forecasting with XGboost

# Evaluation

Submitted predictions are evaluated using mean squared logarithmic error multiplied by 100.