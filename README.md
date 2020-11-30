# Moscow Apartment Price Estimator: Data Science end to end Project Overview

Created a tool that estimates moscow apartment prices (MAE ~ $31.8) to help consumers find the best deal.

1 - Carried out EDA on moscow apartment prices and finding key insights.

2.0 - Optimized Linear, Lasso, Decision Tree and Random Forest Regressors using GridsearchCV to reach the best model.


# Code and Resources Used

**Python Version**: 3.7

**Packages**: pandas, numpy, sklearn, matplotlib, seaborn, json, pickle

**Data Resource**: https://www.kaggle.com/alexeyleshchenko/moscow-apartment-listings


# [EDA](https://github.com/Jaspreetsm21/moscow_apartment_prices/blob/main/Data%20Cleaning%20and%20EDA.ipynb)

![](images/EDA_1.PNG) ![](images/EDA_2.PNG)

![](images/EDA_3.PNG) ![](images/EDA_4.PNG)


## Insight

- There is a trend, we can see new build and older building have higher values compare to 20 to 75 year old buildings.
- Having 2 bedroom Apartment increase the price by 26% compare to 1 bedroom on average.
- There is a clear trend, we can see the higher floor equates to more expensive apartment.
- There is a clear correlation between more square feet and expensive apartments.
- New Apartments (Age 50 below) are build around the city
- Apartments Between 50 and 75 Age are build outside of the center of the city
