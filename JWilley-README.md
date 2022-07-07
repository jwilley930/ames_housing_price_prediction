# Project 2 - Ames Housing Data and Kaggle Challenge

### Problem Statement

As an employee for Zillow, create a model that best predicts sale prices for houses in Ames, IA based on all available data

#### Background

All information to create the models is from the train.csv dataset. It will be used to predict the test the sale prices of the properties in the test.csv dataset.

#### Datasets
- Original training dataset(train.csv)
- Original test dataset (test.csv)
- Cleaned training dataset (test_filled_encoded.csv)
- Cleaned test dataset (train_filled_encoded.csv)
- Sample submission (sample_sub_reg.csv)
- Kaggle submission (submission.csv)

#### Process for cleaning and modelling
- Separated the numeric and categorical values
- Imputed missing values
- Converted the ordinal values to numeric
- Encoded remaining categorical values
- Created models for LR, Ridge, Lasso, ElasticNet, and KNN
- Performed transformations and retested models to find best fit

#### Conclusions

- The LassoCV model using the scaled data is the best of the models we created to predict sale price.
- In future models, pipelines would allow for faster creation of models.
- Gridsearch may be able to fine tune the model even further to improve results.
