# Neural Network Charity Analysis

## Overview

AlphabetSoup, a philanthropic non-profit foundation, provides grant money to non-profit organizations. This project seeks to use deep machine learning models to predict which potential AlphabetSoup grantees have the greatest chance of success in their endeavors.

## Results

### Data Preprocessing

- The target variable for this model, "IS_SUCCESSFUL," is the variable that differentriates a "successful" organization from an "unsuccessful" one
- The feature variables for this model include "APPLICATION_TYPE," "AFFILIATION," "CLASSIFICATION," "USE_CASE," "ORGANIZATION," "AFFILIATION," "STATUS," "INCOME_AMT," "SPECIAL_CONSIDERATIONS," "ASK_AMT"
- Variables that have been removed from the dataframe are unique identifiers for each organization, "EIN" and "NAME"

### Compiling, Training, and Evaluating the Model

- Accross all hidden layers, neurons were increased from 13 to 17 and the number of hidden layers were increased from 2 to 3. RELu and Sigmoid were the activation functions used to test the model. The number of neurons and hidden layers were increased into order to increase the testing factors.
- Event with the adjustments, The target model performance of 75% was not acheived.
- In order to attempt to increase model performance, the dataset was increased in the binning steps. The number of hidden layers was increased from 1 to 2. Intitally, the number of neurons was decreased, then later increased. 

## Summary

Overall, the results of the learning model, at optimal performance, did not exceed 73% accuracy. This is a decent, though perhaps not optimal, success rate. Perhaps a random forest classifier model would improve the success rate of the predictive model at hand.
