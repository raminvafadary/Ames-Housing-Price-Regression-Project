# ![](https://ga-dash.s3.amazonaws.com/production/assets/logo-9f88ae6c9c3871690e33280fcf557f33.png) Project 2: Ames Housing price Recommendation

### Introduction
In this project, we are going to create a regression model based on the Ames Housing Dataset.This model will predict the price of a house at sale and can be used to give advice to people to increase their houses price by improving some features in their houses. like all the data science projects at first, data cleaning and exploratory analysis has been done. second, by data visuallization an insight about the data is driven. third, by feature engineering new features are produced. fourth, a linear regression model is fitted. finally, the model has been evaluated and improved to be used as a house price predictor. 

---

### Datasets
 The Ames Housing Dataset is an exceptionally detailed and robust dataset with over 70 columns of different features relating to houses. 

### Data Dictionary
 
since the dataset is big a description of the dataset is provided here: http://jse.amstat.org/v19n3/decock/DataDocumentation.txt.

---


### Exploratory Data Analysis

Some trends have been identified by data analysis. best features that have the most relatioship to the house price are selected for modeling purpose. 

---


### Feature Engineering

some feature engineering methods like f-test, variance threshold and regularization are used to select the best features for modeling purpose and improving the exsiting models. 

---


### Modeling process

The regression model is generated using the training data.this process is thru these steps:
-train-test split
-cross-validation / grid searching for hyperparameters
-strong exploratory data analysis to question correlation and relationship across predictive variables
-the values for the target column are predicted in the test dataset. 
-the predictions are submitted to Kaggle to see how the model deos against unknown data.



---


### Conclusion/Recommendation

The features that could add most value to a home are large living area, high overall quality and the lot areas. and the features that could hurt the value of a home the most are low overall quality, low kitchen quality and low exterior material quality. one recommendation for the homeowners to increase their house price is improving their house quality by remodeling the house. Future work could be make the model more universal by decreasing the number of features used in the model, in other word selecting the best features to predict a house price.  


