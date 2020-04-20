# KC Housing Regression

## Project Purpose and Description

In this project, we looked at the the various features that influence the price of a home in King's County.  We analyzed  these features, developed and tested models that would predict the price of the home.

## Data:
The data used was in the form of a csv from Kaggle.

<ins> Features </ins>

Over 20,000 data points

id, date, price, bedrooms, bathrooms, sqft_living, sqft_loft, floors, waterfront, view, condition, grade, sqft_above, sqft_basement, yr_built, yr_renovated, zipcode, latitude, and longitude. 
![](images/hist.png)

	
## Tools (all using Python and its various libraries)
   - Pandas
   - Numpy
   - Seaborn
   - Matplotlib
   - Scikit Learn
## Taking a Closer Look at the Data
![](images/corr.png)

## Modeling
After cleaning the data, examining various correlations, feature engineering, and determining it the dataset was a good candidate for a Linear Regression, we were able to run a model and achieve an accuracy rate of 77%. To do some further modeling, we also used a Ridge Regression which yielded an 86% accuaracy rate.
<img src="images/ols_results.png>
![](images/ols_results.png)

 

