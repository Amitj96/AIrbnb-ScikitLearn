# Airbnb-ScikitLearn
In this project, I have used NYC Airbnb data from Kaggle. I have already worked on this data set using pyspark and you can check out that repository.
Here I have tried to predict the price of a listing on Airbnb based on various attributes of the property.
I used pandas and numpy for EDA and scikit learn for Machine learning.
Algorithms used were simple linear regression, Lasso Regression and random forest regressor. 
I have also found out which features affect the price the most. Coefficients can be seen for LR amd L1 and Feature importance can be collected from random forest model.
Some interesting Insights:
Entire home/Apt tend to be more expensive and Shared room the least expensive

Manhattan and Brooklyn have the highest average price while Bronx has the lowest average price

There are five major neighbourhood groups and 229 neighboorhoods in NYC

The length of description of listing has no impact on user

The maximum listing per host is 238

The average Airbnb listing price in NYC per night is $107

Most Expensive neighbourhood: Vinegar Hill

Least Expensive neighbourhood: Inwood

