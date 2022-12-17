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

R-squared is 0.7149, which is a strong correlation for the dataset and shows the dataset is an effective dataset. However, r-squared is not the only consideration for effectiveness. There may be other variables not included in the dataset contributing to the variation in the mpg.


## Summary Statistics on Suspension Coils

### The design specifications for the MechaCar suspension coils dictate that the variance of the suspension coils must not exceed 100 pounds per square inch. Does the current manufacturing data meet this design specification for all manufacturing lots in total and each lot individually? Why or why not?




## T-Tests on Suspension Coils
### T-test summary and corresponding screenshots



## Study Design: MechaCar vs Competition
### What metric or metrics are you going to test?


### What is the null hypothesis or alternative hypothesis?


### What statistical test would you use to test the hypothesis? And why?



### What data is needed to run the statistical test?

