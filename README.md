## Features that Influence Antler Size in Mature Male White-tailed-Deer
### I wanted to see what features influence antler size of mature (4.5- and 5.5-year-old) male white-tailed deer.
* Data: This is a unique dataset from a captive colony of white-tailed deer with known age, antler mass (kg), and maternal / paternal parentage.
* Each male was fed ab libitum one of two kinds of pelleted feed that differed in digestible energy, but had similar protein percentage (16%) from the time they were weaned. The standard energy diet 'S' had 2.65 kcal/g of dietary energy and the low energy diet 'L' had 1.77 kcal/g of dietary energy.

## Methods: 
* Model seletion: These datasets are very small (<100 rows), thus, I used cross-validation to select between three models: random forest, gradient boosting, and xgboosting regressor models
* Feature importance: fit selected models to the 4.5- and 5.5-year-olds dataset to assess important features

## Findings 

### A. 4.5-year-olds
* Antler size of 4.5-year-old males is most influenced by the body mass of the male, which is not surprising, but useful to know for certain. 
* 'Birth wt' is more predictive of antler size in 4.5-year-olds than in 5.5-year-olds.
* The mother ('DID') and father ('DID') were predictive of antler size.
* What's most surprising here is that, when it comes to determing antler size of mature males, it didn't really matter whether males had been eating a low or high energy diet ('Energy') throughout their life.  

![image](https://user-images.githubusercontent.com/95881308/180613412-75e6a84b-adcb-4da0-bfb5-dc8cf2907c6e.png)

###  B. 5.5-year-olds
* Body mass is also the most influential feature of antler size in 5.5-year-old males.
* The mother ('DID') and father ('DID') were predictive of antler size.
* Like in 4.5-year-olds, available dietary energy (high versus low; 'Energy') was not very influential.

![image](https://user-images.githubusercontent.com/95881308/180613432-ff440678-a9f7-4424-bc4e-b74e992a5991.png)
