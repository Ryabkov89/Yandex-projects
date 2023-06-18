# Forecast of a next-hour taxi traffic

## Project description.
The taxi company has collected historical data on taxi orders at airports. To attract more drivers during peak load, you need to predict the number of taxi orders for the next hour. A model is being built for such a prediction.To study and build a prediction model, it is necessary to analyze the data obtained and identify patterns that affect the number of orders.
## Tools and technologies
* pandas
* nympy
* matplotlib
* statsmodels
  * seasonal_decompose
* sklearn
  * TimeSeriesSplit
  * cross_val
  * mse
  * LinearRegression
  * train_test_split
* catboost
  
## Conclusion
A study was conducted on historical data on taxi orders at airports.
During the study , the following patterns were identified:

- The total increase in the number of taxi orders: more than doubled in half a year.
- Increased demand from Friday evening to early Saturday morning and from Sunday night to Monday afternoon.
- Reduced demand on Sundays
- Increased demand at midnight
- Reduced demand between 6 and 7 a.m.
Based on the analysis, several models were built and trained (Linear Regression, CatBoost and DecisionTreeRegressor), according to the results of cross-validation on a training sample, the best RMSE metric was found in the CatBoost model with a tree depth of 15 and the number of iterations of 1000. The model performed satisfactorily on a test sample with RMSE metrics
