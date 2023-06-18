# Toxic comments detector

## Project description.
The online store is launching a new service. Now users can edit and supplement product descriptions, as in wiki communities. That is, clients offer their edits and comment on the changes of others. A tool is required that will search for toxic comments and send them for moderation.
## Tools and technologies
* pandas
* numpy
* nltk
* matplotlib
* spacy
* sklearn
* catboost
## Conclusion
To perform the classification task, it was decided to use the data transformed using tf-idf.  
Based on the obtained features, hyperparameters of several models were trained and configured: logistic regression, gradient boosting and a decision tree. As a result, the best model is gradient boosting CatBoost

