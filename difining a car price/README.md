# Prediction of used car price

## Project description.
The service for the sale of used cars is developing an application to attract new customers. In it, you can quickly find out the market value of your car. Based on historical data, it is necessary to build a model to determine the cost of the car.

Important to the customer:

- prediction quality;
- prediction speed;
- training time.
## Tools and technologies
* pandas
* matplotlib
* sklearn
  * RandomizedSearchCV
  * Pipeline
  * OHE
  * StandardScaler
  * OrdinalEncoder
  * r2_score
  * mse
  * LinearRegression
  * RandomForestRegressor
  * make_column_transformer
* numpy
* catboost
  * Pool
  * CV
## Conclusion
The analysis showed the following advantages and disadvantages of the models:
- Lightgdm gradient boosting technology
-- fast operation speed
-- good metrics of model quality
-- data must be prepared manually (coding, scaling)
- Catboost gradient boosting technology
-- fast operation speed
-- the best metrics of model quality
-- simplicity
-- data can be "fed" to the model in "raw form", coding of categorical features and scaling is performed by the model
- Linear regression
-- fast operation speed
-- simplicity
-- unsatisfactory quality metrics
- Random forest
-- good quality metrics
-- a very long time is spent on the selection of the model
-- coding and scaling of features in manual mode
