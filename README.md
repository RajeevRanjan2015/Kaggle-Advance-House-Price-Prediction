# Kaggle-Advance-House-Price-Prediction

Regression problem to predict price of the house in Ames.

## Aim:

We are asked to predict sale prices for residential real estate properties from describing features. We have a training set with 1460 observations and corresponding prices (labelled). We need to make predictions for 1459 observations where the price is not known to us.

## Data Set:

The dataset contains data of individual residential properties in Ames, Iowa from 2006 to 2010. The full dataset consists of 2930 samples with 80 features. The Ames Housing Data Set was collected by Dean De Cock, Professor of Statistics at Truman State University, in 2011.

## Statistics about data set:

80 variables in total: 23 nominal, 23 ordinal, 14 discrete and 20 continuous.
20 continuous: relate to various area dimensions (e.g. lot size, total dwelling square footage etc.)
14 discrete: quantify number of items occurring in the house (e.g. kitchens, baths, etc.)
46 categorical ranging from 2 to 28 classes

## Approach taken:

1.EDA  
2.Data Cleaning (missing value, wrong value, wrong data type, skewness, outliers)  
3.Feature Engineering.
4.Use some ML algorithm to predict the SalePrice  
5.Perform Hyperparameter tunning for the best performing algorithm  
6.Use full dataset to train model and predict for the test data set and submit the result.  


## Result:

sample_submission.csv file need to be submitted for evaluation.
