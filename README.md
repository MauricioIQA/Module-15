# Module15-Challenge
## Overview
The purpose of this analysis is to compare statistical data in order to get usefull insigths regarding different vehicle variables and parameters using R.

## Linear Regression to Predict MPG
![linear_regression](https://github.com/MauricioIQA/Module-15/blob/main/1.PNG)  
From the summary of linear regression model, we can appreciate vehicle_length, ground_clearance and vehicle_weight are statistically significant since there p-values are under the confident level 0.05. We can safely asumme that the model fits the data well and it can accurately predict the MPG.
## Summary Statistics on Suspension Coils
![t.test_overall](https://github.com/MauricioIQA/Module-15/blob/main/2.PNG)  
The p-value > 0.05, meaning not enought statistical evidence to reject null hypothesis.  
### T.test on Lot 1
![t.test_lot1](https://github.com/MauricioIQA/Module-15/blob/main/3.PNG)  
### T.test on Lot 2
![t.test_lot2](https://github.com/MauricioIQA/Module-15/blob/main/4.PNG) 
### T.test on Lot 3
![t.test_lot3](https://github.com/MauricioIQA/Module-15/blob/main/5.PNG)  
Lot 1 and Lot 2 are not statistically significant. The Lot 3 is significant, p-value = 0.04168 < 0.05.

## Study Design: MechaCar vs Competition
Another study migth be performed under the maintenance cost 
 - The metric to review is maintenance cost.
 - Null Hypothesis: maintenance cost has insignificant relations with MPG. 
 - Alternative Hypothesis: maintenance cost don't have significant relations with MPG.
 - (1) Linear regression model will be used to test the relationship between  maintenance cost and MPG.
 - (2) Using anova test to test maintenance cost based on number of components.
 - Further data needed to be collected is average maintenance cost of vehicles.
