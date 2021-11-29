# MechaCar_Statistical_Analysis

## Linear Regression to Predict MPG
#### Which variables/coefficients provided a non-random amount of variance to the mpg values in the dataset?
- Vehicle weight, vehicle weight, ground clerance, and all wheel-drive are all unlikely to provide a random amound of variance per their Pr(>|t|) values.

#### Is the slope of the linear model considered to be zero? Why or why not?
- The slope is not considered to be zero. The multiple R-squared is .7149 which indicates that over 70% of of the variability of the MPG is explained using this model. As well the p-value is 5.35e-11 indicating that this is statistically significant.
#### Does this linear model predict mpg of MechaCar prototypes effectively? Why or why not?
- This model effectively predicts that mpg of MechaCar Prototypes effectively. The values of the multiple R-squared and p-value suggests that over 70% of the variability of the mpg is explained using the variables in our model and is statistically significant.

## Summary Statistics on Suspension Coils

The design specifications for the MechaCar suspension coils dictate that the variance of the suspension coils must not exceed 100 pounds per square inch. Does the current manufacturing data meet this design specification for all manufacturing lots in total and each lot individually? Why or why not?
- The current manufacturing data suggest that the total variance of all lots does meet current design specifications. Individually, Lot 3 does not meet the design specification. Its current variance is 170.28 pounds per square inch.  

## T-Tests on Suspension Coils

- Based on the results of the t-test for the total lots and for each individual lot, there is no statistical difference between the samples and the mean of 1500. 

## Study Design: MechaCar vs Competition

A statistical study can be performed to quantify the performance of the MechaCar aginst competitor vehicles. To test for performance we suggest mpg, safety ratings, acceleration, fuel efficiency, horse power, and price as variables. The null hypothesis will test if there is a difference between the MechaCar and its competitors through these metrics. An ANOVA test will be used to test the statistical diffreence between these samples. Data about similar class vehicles from other manufactures will need to be collected to accurately quantify these metrics. 
