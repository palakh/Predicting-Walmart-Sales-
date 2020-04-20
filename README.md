# Predicting-Walmart-Sales

![](https://static01.nyt.com/images/2012/02/08/business/08walmart-pic/08walmart-pic-articleLarge.jpg)
## PROBLEM STATEMENT
We want to predict Walmart weekly sales. This forecasting has multiple applications -
* Sales Planning
* Demand Forecasting
* Financial Planning
* Internal Controls

## DATASET 
Dataset has been obtained from Kaggle: https://www.kaggle.com/c/walmart-recruiting-store-sales-forecasting

It covers daily sales for 45 stores from to 2010-02-05 to 2012-11-01. The training dataset has been rolled up to weekly analysis. The final training dataset independent features - 
* Weekly Sales (dependent variable)
* Whether the week included a public holiday
* Average temperature for the week
* Average fuel price for the week
* Unemployment during the week
* Shop size
* CPI
* Date (we converted these into dummy variables for each month with baseline July)

** Removed data related to “mark downs” due to substantial gaps in information

## MODELS USED
* *k-NN* 
* *Linear Regression*
* *Lasso & Ridge* 
* *Regression Trees*
* *Random Forest* 
* *Bagging*
* *Boosting*

## Results
* Random Forest performed the best for predicting the sales. The model improved from a baseline error of 20% to 8%.
* Size and CPI are the dominant features driving sales for a store 

## Further Recommendations
* Collect the missing “mark down” data
* More detailed data: product information rather than store information could provide more useful information for making business         decisions like managing inventory and understanding product trends

## REPOSITORY DETAILS
Access -
1. [Final Presentation - Summary of Approach and Results](https://github.com/palakh/Predicting-Walmart-Sales-/blob/master/Walmart%20Analysis.pdf)
2. [Final Code](https://github.com/palakh/Predicting-Walmart-Sales-/blob/master/code.rmd)
