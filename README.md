# Machine Learning Analysis

About the Data:

Over a period of nine years in deep space, the NASA Kepler space telescope has been out on a planet-hunting mission to discover hidden planets outside of our solar system.

The dataset used in this analysis is a cumulative record of all observed Kepler "objects of interest" — all of the approximately 10,000 exoplanet candidates Kepler has taken observations on.

Data Source: https://www.kaggle.com/nasa/kepler-exoplanet-search-results

Model Comparison:

To process the data, I created maching learning models to classify candidatee exoplanets from the raw dataset. I trained and tested two different Support Vecor Classification (SVC) models to conduct my analysis. I first hyperparameter tuned and tested a linear classification, and found the best grid score (Mean cross-validated score of the best_estimator) to be 88%. I then used an RBF classifier and found the best grid score to be 87%.

Though both of these models generated close grid scores, neither is quite good enough to predict the existense of new exoplanets. Creating more robust models with additional scoring parameters would likely result in a better prediction model.
