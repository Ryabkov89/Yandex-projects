# Defining a better place for an oil field

## Project description.
We need to decide where to drill a new well.

You have been provided with oil samples in three regions: in each 10,000 fields, where the quality of oil and the volume of its reserves were measured. Build a machine learning model that will help determine the region where mining will bring the greatest profit. Analyze the possible profits and risks with the *Bootstrap technique.*

Steps to select a location:

- They are looking for deposits in the selected region, the values of the signs are determined for each;
- Build a model and estimate the volume of stocks;
- Choose the deposits with the highest estimates of values. The number of deposits depends on the company's budget and the cost of developing one well;
- Profit is equal to the total profit of the selected fields.
## Tools and technologies
* pandas
* numpy
* sklearn
  * StandardScaler
  * train_test_split
  * LinearRegression
  * mse
* matplotlib
## Conclusion
According to the combination of factors, after the analysis and calculation of profits and risks, it was determined that the most promising region for the development of the field is region number 2, the probability of losses is no more than 1%, which suits us unlike other regions, where despite the possibility of obtaining more profit, the risk of going into loss is also high.
