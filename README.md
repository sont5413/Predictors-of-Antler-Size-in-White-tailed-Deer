## Features that Influence Antler Size in Mature Male White-tailed-Deer

![image](https://user-images.githubusercontent.com/95881308/197414332-b63d3c9c-1810-4ee7-94ac-6720c01d1ddd.png)

### I wanted to see what features influence antler size of white-tailed deer.
* Data: This is a unique dataset from a captive colony of white-tailed deer with known age, antler mass (kg), and maternal / paternal parentage.
* Each male was fed ab libitum one of two kinds of pelleted feed that differed in digestible energy, but had similar protein percentage (16%) from the time they were weaned. The standard energy diet 'S' had 2.65 kcal/g of dietary energy and the low energy diet 'L' had 1.77 kcal/g of dietary energy.

## Methods: 
* Model building and selection: linear regression, random forest (rf), gradient boosting (gb), and extreme gradient boosting (xgbr) models
* Tuned hyperparameters via grid search
* Feature importance: compare and contrast feature importances from ML models
  * The xgbr model achieve the lowest MAE after tuning, which was lower than the linear regression model. 

## Findings 

### A. Important features from the XGBR model: 
![image](https://user-images.githubusercontent.com/95881308/206016737-c7e7d951-6408-4aeb-a2e3-3d4bfecaecd8.png)

Body Mass was the most important feature and far and away more predictive than any of the other features.
