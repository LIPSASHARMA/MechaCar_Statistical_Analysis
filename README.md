# MechaCar_Statistical_Analysis


## Linear Regression to Predict MPG

### Which variables/coefficients provided a non-random amount of variance to the mpg values in the dataset?

AWD: 0.19 >= 0.05, it is not meaningful, it has a random variance
MPG: 0 < 0.05, it is meaningful, it has non-random variance
Ground Clearance: 0 > 0.05 it is meaningful, it has non-random variance
Spoiler Angle: 0.31 > 0.05 it is not meaningful, it has a random variance
Vehicle Length: 0 < 0.05, it is meaningful, it has non-random variance
Vehicle Weight: 0.08 > 0.05 it is not meaningful, it has a random variance


### Is the slope of the linear model considered to be zero? Why or why not?

The MLR for mpg = -0.01 + 6.267 + 0.001 + 0.069 + 3.546 -3.411, gives me a non-zero slope.

All of the slopes of the variables are close to zero:

AWD: -3.411
ground clearance: 3.546
spoiler angle: 0.069
vehicle length: 6.267
vehicle weight: 0.001

### Does this linear model predict mpg of MechaCar prototypes effectively? Why or why not?

R-squared should not be used for effectiveness. There are ther variables, like air drag coefficient, etc. that are not included in the calculation of the variation of mpg. 
R-squared = 0.7149 this indicates a strong correlation and also highlights it is a effective dataset. 


## Summary Statistics on Suspension Coils

### The design specifications for the MechaCar suspension coils dictate that the variance of the suspension coils must not exceed 100 pounds per square inch. Does the current manufacturing data meet this design specification for all manufacturing lots in total and each lot individually? Why or why not?

Lot 1 and Lot 2 have lower variance. 
The total manufacturing lot variance is 62, which is within the expectations as it is under 100. 
However, Lot 3 shows high variance. Lot 3 variance is 170 and does not meet the specifications as its over 100. 

#### Manufacturing LOT Summary
Below is the summary of manufacturing Lot

![ScreenShot](https://github.com/LIPSASHARMA/MechaCar_Statistical_Analysis/blob/main/images/1_total_summary.png)


#### Manfacturing LOT Number Summary
Below is the summary of each lot-1,2,3

![ScreenShot](https://github.com/LIPSASHARMA/MechaCar_Statistical_Analysis/blob/main/images/2_lot_summary.png)


## T-Tests on Suspension Coils
### T-test summary and corresponding screenshots


![ScreenShot](https://github.com/LIPSASHARMA/MechaCar_Statistical_Analysis/blob/main/images/5_T-test_summary.png)


![ScreenShot](https://github.com/LIPSASHARMA/MechaCar_Statistical_Analysis/blob/main/images/6_T-test_lot1.png)


![ScreenShot](https://github.com/LIPSASHARMA/MechaCar_Statistical_Analysis/blob/main/images/7_T-test_lot2.png)


![ScreenShot](https://github.com/LIPSASHARMA/MechaCar_Statistical_Analysis/blob/main/images/8_T-test_lot3.png)



## Study Design: MechaCar vs Competition
### What metric or metrics are you going to test?


### What is the null hypothesis or alternative hypothesis?


### What statistical test would you use to test the hypothesis? And why?



### What data is needed to run the statistical test?

