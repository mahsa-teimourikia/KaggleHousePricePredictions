# KaggleHousePricePredictions
Kaggle's "House Price Prediction" using Regression techniques.

This notebook is created to predict house prices based on [Ames Housing dataset](http://www.amstat.org/publications/jse/v19n3/decock.pdf). The Kaggle competition is found [here](https://www.kaggle.com/c/house-prices-advanced-regression-techniques)

File descriptions:
* train.csv - the training set
* test.csv - the test set
* data_description.txt - full description of each column, originally prepared by Dean De Cock but lightly edited to match the column names used here

For arriving to the predictions, I have used a weighted mean of the results of the following models:
* Lasso Regression
* Elastic Ridge Regression
* Kernel Ridge Regression
* Gradient Boosting Regression
* XGBoost
* LightGBM

The next step in improving the results would be adding the model stacking to the solution.
