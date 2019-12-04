## Predicting King County Housing Prices
We looked at King County, WA housing prices from 5/2014-5/2015 dataset to find out which variables were the dominant factors in housing prices.

## Contributors 
 -Christopher Shaw ([github](https://github.com/JackBurton11/))
 -Mehmet Toprak ([github](https://github.com/toprakmehmet/))

## Background
This was our 3rd 2 day project at the Flatiron School (NYC Data Science)

## Project Purpose and Description
 - The goal of this project was to work with real world datasets and experiment with different types of regression(linear, lasso, ridge) to create a predictive model. 
 
## Data:
 - **Kaggle**
	- House Sales in King County, USA
	- www.kaggle.com

## Python Tools:
   - pandas
   - statsmodels
   - sklearn
   - Seaborn/Matplotlib
   - SciPy/NumPy

## Process
We experimented with several different types of regression and spent a lot of time on feature selection to try to build the best possible model. Our data had 21 columns, many of which we removed entirely due to collinearity and other factors. Our biggest change was turning our 70 different zip codes into dummy variables. For our models, we split the dataset using 75% for training and 25% for testing.

## Conclusion
After our model experiments and extensive feature selection, we had good results with that our best model used linear regression. The R2 was 0.87 and the MSE was 0.03.
