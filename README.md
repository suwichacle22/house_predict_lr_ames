# Ames Housing Dataset and Kaggle Challenge
Team: Bird, Anik (Poisson Distribution)
​
# Problem Statement
The Housing Department, City of Ames, is working towards the development of the best actionable and explainable house price prediction model based on the Ames housing dataset from 2010 for the use in city's decision making and policy development.
​
---
# Model Development Summary
The first part of model development was spent on data cleaning, removing outliers, Exploratory Data Analysis (EDA) and encoding. After the data are prepared and ready for use, we started developing price prediction model using Linear Regression.
​
The model development process began with selecting the right features using correlation, Lasso and Ridge. The features and the model are further evaluated by LINEM criteria to leverage model performance. Our final model scored with r-square value of 91% and RMSC values of 28,099 (as evaluated in Kaggle)
​
---
# Conclusion and Recommendation
To sum up, the final model is an actionable and explainable price model based on the current dataset. This model can surely be used by the city of Ames for the purpose of developing an equal and affordable housing policy as well as urban planning programme. Furthermore, the Housing Devision of Ames can also use this model to adjust the appropriate appraisal prices to ensure the accurate tax collection.
​
As an outlook into the future, it should be taken in consideration that there are limitations in the final model. Firstly, the features available in the datasets are mostly physical features of houses. Therefore, it lacks other contextual features such as proximity to parks, schools, supermarkets, etc., which may strongly affect house prices. Furthermore, the current data from 2010 do not capture the situation in 2022. It is highly suggested that City of Ames collect new, updated data with more contextual features. Lastly, it cannot be denied that linear regression model may have less predictive power than other alternatives. Therefore, using other model to predict house prices is also worth considering.
