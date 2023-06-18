# Gold recovery research

## Project description.
A machine learning model is being built for an industrial company that develops solutions for the efficient operation of industrial enterprises. The model should predict the recovery coefficient of gold from gold-bearing ore based on data with extraction and purification parameters. The model will help optimize production so as not to launch an enterprise with unprofitable characteristics.

Data on the purification process of gold-bearing ore purification were obtained. The data contains information on the content of substances in raw materials, products and tailings during flotation, the first and second stages of purification, as well as physical and design characteristics and parametric values of the purification stages.  
Task: to simulate the process of recovery of gold from gold-bearing ore and predict the efficiency of enrichment of the rough and final product based on the initial data
## Tools and technologies
* pandas
* nympy
* matplotlib
* sklearn
  * mae
  * LinearRegression
  * DecisionTreeRegressor
  * RandomForestRegressor
  * cross_val_score
  * make_scorer

  
## Conclusion
We have obtained data on the recovery process of gold from gold-bearing ore. During the study, the entire process was modeled and tested on test data.
The highest quality model is the decisive forest, the model is trained and tested
