# Optimizing electricity consumption

## Project description.
In order to optimize production costs, the metallurgical plant decided to reduce electricity consumption at the steel processing stage. It is necessary to build a model that will predict the temperature of steel.
## Tools and technologies
* pandas
* nympy
* matplotlib
* seaborn
* sklearn
  * GridSearchCV
  * RandomizedSearchCV
  * StandardScaler
  * Pipeline
  * Lasso
  * Ridge
  * ElasticNet
  * RandomForestRegressor
  * PCA
* catboost
  * Pool
  * CV

  
## Conclusion
After analyzing the results of the model, the factors that make the greatest contribution to the value of the final temperature were identified:
- Initial temperature (1st measurement)
- Total power (square root of the sum of squares of active and reactive power)
Based on the simulation results, additional recommendations are given for a deeper analysis for further optimization of energy resources:
- determination of the normal limits of temperature fluctuations
- fixing temperature deviations from the set limits
- collection and analysis of production data for such deviations
- root cause analysis and hypothesis testing
- development of energy-saving measures
- 

