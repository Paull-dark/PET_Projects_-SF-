The goal of the project was to using several different model to get a best score of MAPE when predicting the price of auto.

In this project I used:

LightGBM;
CatBoost,
Keras Sequental,
Tensorflow.

Unfortunatelly, I was not able hit the score less than 12%.

Neural networks shows in general worse results than conventional models (at least in this project)

It was decided to use model ensembling for submission (LGBM, CATboost and regular tabular neural model)

Problems:

The text pre-processing taking a lot of time. It was applied lemmatization and manual cleaning of strings.
But the results are still not perfect.

It was decided manually create features based on EDA sentiment analysis.

How to improve:

Delete useless columns from dataframe.
Play with parameters.