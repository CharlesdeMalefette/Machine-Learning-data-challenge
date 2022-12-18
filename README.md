# Data Challenge INF554 

Author: 
Clément Garancini: clement.garancini@polytechnique.edu

Jean Dimier de la Brunetière: jean.dimier-de-la-brunetiere@polytechnique.edu

Charles de Malefette: charles.de-malefette@polytechnique.edu


## Content
This notebook project provides a pipeline to predict the number of retweet given a certain number of features concerning this tweet. We will use the dataset "train.csv" available in the same folder han this readme. 

### For testing on your own data:
In the folder containing the notebook, add your file "test.csv" containing the dataset with every features except "retweets_count" which is the feature to predict. 

Go on the notebook cgcd and run the folliowing cells in this order: 

- Imports cells
- Cells to run 

This will apply our models saved as "cgcd_model.json" and will save the prediction in a file called "test_data_pred.csv" available in the same folder. This file has 2 columns: TweetID  and retweets_count.

### Library used:
Running thid project recquires some libraries: 
- Numpy
- Pandas
- Matplotlib
- sklearn
- xgboost

### Documentation
- XGBoost documentation: XGBoost implements an algorithm of gradient boosting. We used it as a regressor. 
Link : https://xgboost.readthedocs.io/en/stable/parameter.html

-