
### problem statement
In this project, we are going to create a regression model based on the Ames Housing Dataset.This model will predict the price of a house at sale and can be used to give advice to people to increase their houses price by improving some features in their houses. like all the data science projects at first, data cleaning and exploratory analysis has been done. second, by data visuallization an insight about the data is driven. third, by feature engineering new features are produced. fourth, a linear regression model is fitted. finally, the model has been evaluated and improved to be used as a house price predictor. 

---

### Dataset
 The Ames Housing Dataset is an exceptionally detailed and robust dataset with over 70 columns of different features relating to houses. 

### Data Dictionary
 
since the dataset is big a description of the dataset is provided here: http://jse.amstat.org/v19n3/decock/DataDocumentation.txt.

---


### Data Cleaning and Exploratory Data Analysis 

at first data is cleaned. the columns with high number of missing values are droped and columns with low number of missing values are imputed. 
Some trends have been identified by data analysis and data visuallization.best features that have the most relationship to the house price are selected for modeling purpose based on the result from data visuallization.

---


### Feature Engineering

the sklearn feature engineering tool (polynomial features) is used to produce new features. categorical variables are dummified using one-hot-encoder. then some feature selection methods like f-test and variance threshold are used to select the best features for modeling purpose and improving the exsiting models.

---


### Modeling process

The regression model is generated using the training data and evaluated using test data.this process is thru these steps:

- train-test split
- cross-validation / grid searching for hyperparameters 
- making prediction for test data and plot the results
- model evaluation using metrics like R2 and RMSE
- getting the model coefficients for interpretation
- the predictions are submitted to Kaggle to see how the model deos against unknown data.



---


### Conclusion/Recommendation

 The model had the R2 score of %92 and RMSE of $20,000. from the model coefficients we found that the features that could add most value to a home are large living area, high overall quality and the lot areas. and the features that could hurt the value of a home the most are low overall quality, low kitchen quality and low exterior material quality. one recommendation for the homeowners to increase their house price is improving their house quality by remodeling the house. Future work could be make the model more universal by decreasing the number of features used in the model, in other word selecting the best features to predict a house price.  


