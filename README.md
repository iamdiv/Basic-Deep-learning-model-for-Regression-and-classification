# Basic-Deep-learning-model-for-Regression-and-classification

1 -  Classication Problem\n
For classification 'crime-classification.ipynb' notebook has been created
I used San Francisco Crime Classification dataset - https://www.kaggle.com/c/sf-crime/data 

Data fields
Dates - timestamp of the crime incident
Category - category of the crime incident (only in train.csv). This is the target variable you are going to predict.
Descript - detailed description of the crime incident (only in train.csv)
DayOfWeek - the day of the week
PdDistrict - name of the Police Department District
Resolution - how the crime incident was resolved (only in train.csv)
Address - the approximate street address of the crime incident 
X - Longitude
Y - Latitude

2 - Regression Problem 
For Regression problem 'Revenue_prediction.ipynb' has been created
I used Restaurant Revenue prediction Dataset - https://www.kaggle.com/c/restaurant-revenue-prediction/data 

Data fields
Id : Restaurant id. 
Open Date : opening date for a restaurant
City : City that the restaurant is in. Note that there are unicode in the names. 
City Group: Type of the city. Big cities, or Other. 
Type: Type of the restaurant. FC: Food Court, IL: Inline, DT: Drive Thru, MB: Mobile
P1, P2 - P37: There are three categories of these obfuscated data. Demographic data are gathered from third party providers with GIS systems. These include population in any given area, age and gender distribution, development scales. Real estate data mainly relate to the m2 of the location, front facade of the location, car park availability. Commercial data mainly include the existence of points of interest including schools, banks, other QSR operators.
Revenue: The revenue column indicates a (transformed) revenue of the restaurant in a given year and is the target of predictive analysis. Please note that the values are transformed so they don't mean real dollar values
