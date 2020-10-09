# Statistical_Analysis_Multiple_Linear_Regression
##
The goal of this project is to forecast the housing price of King County.
The data is from [Kaggle.com](https://www.kaggle.com/shivachandel/kc-house-data/tasks).
##
Online property companies offer valuations of houses using machine learning techniques. The aim of this report is to predict the house sales in King County, Washington State, USA using Multiple Linear Regression (MLR). The dataset consisted of historic data of houses sold between May 2014 to May 2015.
We will predict the sales of houses in King County with an accuracy of at least 75-80% and understand which factors are responsible for higher property value - $650K and above.”

The dataset consists of house prices from King County an area in the US State of Washington, this data also covers Seattle. The dataset was obtained from Kaggle. This data was published/released under CC0: Public Domain. Unfortunately, the user has not indicated the source of the data. Please find the citation and database description in the Glossary and Bibliography.
The dataset consisted of 21 variables and 21613 observations.
## Data Cleaning & EDA
In this section, some important features were selected for analyzing based on the feature information. For example, the square feet of the house and the numbers of the house. Obviously, normally the bigger size the house is, the more room there might be, and one variable can partially explain another one. So in order to avoid multicollinearity, I selected variables that can explain the independent variables well.

### The changes housing price by time
![image/price.png](image/price.png)
We can see that the mean of the price is stabel and there is one big fluctuation between 2014 09 29  to 2014 11 18.
In order to add up dummy variable, the zipcodes were converted into city names using uszipcode library, then convert those cities into dummy variables.
###  Distribution of features and feature Engieering
####  Distribution of Features & Outlier Removel  - Before
![image/feature_distribution _before.png](image/feature_distribution _before.png)
####  Distribution of Features & Outlier Removel - After
![image/distribution_after.png](image/distribution_after.png)
### More EDA
#### Price VS Bedroom
![image/bedroom_vs_price.png](image/bedroom_vs_price.png)
#### Price VS sqft_living - Linearity and Homoskedasticity
![image/sqft_living_vs_price.png](image/sqft_living_vs_price.png)
#### Basement VS Price 
![image/basement_vs_price.png](image/basement_vs_price.png)
#### Condition vs Price 
![image/condition_vs_price.png](image/condition_vs_price.png)
####  Grade vs Price
![image/grade_vs_price.png](image/grade_vs_price.png)
#### Building   Age VS Price
![image/building_age_vs_price.png](image/building_age_vs_price.png)
#### Cities VS Price
![image/kc_map.png](image/kc_map.png)


