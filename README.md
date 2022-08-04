# MechaCar_Statistical_Analysis

## Linear Regression to Predict MPG
The screenshot below shows the results of producing a linear regression model to predict MPG from the MechaCar_mpg dataset using the variables of vehicle length, vehicle weight, spoiler angle, ground clearance, and AWD. Of these variables, vehicle length and ground clearance provided a non-random amount of variance to the mpg values in the dataset, as shown by their low p-values. The slope of the linear model is not considered to be zero because the estimates for all coefficients are not zero. This model predicts the mpg of MechaCar protoypes effectively because the Adjusted R-squared reflects that ~68.25% of the variation within mpg is explained by the coefficie

# Linear Regression to Predict MPG
![linear_regression_d1](https://user-images.githubusercontent.com/102489511/182971228-7f0508b1-321b-4f16-b3f0-f2f727d5e6c5.png)


# Summary Statistics on Suspension Coils
Summary statistics of the mean, median, variance, and standard deviation of the PSI were pulled and are shown below for the suspension coils overall and for the manufacturing lots. The design specifications for the MechaCar suspension coils dictate that the variance of the suspension coils must not exceed 100 pounds per square inch (PSI). Based on the variance of the suspension coils in the total summary, the suspension coils overall meet the MechaCar design specifications. However, the lot summary shows that while manufacturing Lots 1 and 2 meet the design specifications and have variances under 100 PSI, Lot 3 does not meet the design specifications as its variance is much over the 100 PSI limit.


![2022-08-04 (3)](https://user-images.githubusercontent.com/102489511/182971510-18d70c92-9cde-4acd-9a5d-d6aaafa4c6b8.png)

![2022-08-04 (7)](https://user-images.githubusercontent.com/102489511/182971514-cf7e64fd-14e8-4f10-b973-cfe2b676f01c.png)


## T-Tests on Suspension Coils
T-tests were run on the suspension coil data to determine if all manufacturing lots, and each lot individually, are statistically different from the population mean of 1,500 pounds per square inch (PSI). The results of the t-tests across all lots and each individual lot are below.
![2022-08-04 (8)](https://user-images.githubusercontent.com/102489511/182972512-2993198b-b8ec-42db-ac66-e2c2f38ae147.png)

* Lot1 Suspension Coil T-Test:

The results of the t-test to test if the PSI mean for Lot1 is statistically different from the population mean of 1,500 pounds per square inch show that, at a 95% confidence level, the two means are not statistically different. The p-value of 1 shows that the mean for Lot1 is exactly the same same as the population mean of 1500 PSI

* Lot2 Suspension Coil T-Test

The results of the t-test to test if the PSI mean for Lot2 is statistically different from the population mean of 1,500 pounds per square inch show that, at a 95% confidence level, the two means are not statistically different. Because the p-value of 0.6072 is higher than the critical value of 0.05, the null hypothesis can be accepted in that there is no difference between the means of the PSI for the population and Lot2. The means within the 95% confidence range are between 1499.423 and 1500.977 PSI.

* Lot3 Suspension Coil T-Test:

The results of the t-test to test if the PSI mean for Lot3 is statistically different from the population mean of 1,500 pounds per square inch show that, at a 95% confidence level, the two means are statistically different. Because the p-value of 0.04168 is lower than the critical value of 0.05, the null hypothesis should be rejected in that there is a difference between the means of the PSI for the population and Lot3 and the true mean is not equal to 1500. The means within the 95% confidence range are between 1492.431 and 1499.849 PSI.

![2022-08-04 (9)](https://user-images.githubusercontent.com/102489511/182972530-7adfb5d2-ba2b-424a-aabc-0ca6539e8bec.png)




# Study Design: MechaCar vs Competition
To quantify how the MechaCar performs against the competition, an independent t-test could be used to compare the safety ratings of MechaCar against the competition. An independent t-test could be used because it will compare the means of the two different groups, MechaCar and the competition, to determine whether the associated population means are significantly different. To run this statistical test, ordinal data on the safety ratings for each group is needed. The null hypothesis would be that there is no difference in safety ratings between MechaCar and the competition and the alternative hypothesis is that there is a difference in the safety ratings between those two groups. Further analysis could be done using the results from the t-test


