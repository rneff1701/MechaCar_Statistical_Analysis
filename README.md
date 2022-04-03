# MechaCar_Statistical_Analysis

## Linear Regression to Predict MPG
- Which variables/coefficients provided a non-random amount of variance to the mpg values in the dataset?  The vehicle length and the ground_clearance. 
- Is the slope of the linear model considered to be zero? Why or why not?  The slope of the linear model is not considered to be zero. This is because the linear regression shows that some of the independent variables had a significant effect on the dependent variable.
- Does this linear model predict mpg of MechaCar prototypes effectively? Why or why not?  Yes.  The R squared value is 71.49% which implies that roughly 71% of the time the predictions will be correct using the linear model

## Summary Statistics on Suspension Coils
The Suspension_Coil csv was imported into R and then converted into a data frame.  Two subset tables were then created: Total Summary and Lot Summary.

![total summary df](https://user-images.githubusercontent.com/95188079/161436379-ed967d00-2fed-4e10-87b1-de0752caa031.png)

![lot summary df](https://user-images.githubusercontent.com/95188079/161436390-2fb32857-178e-4b28-9d6f-e9227d3f3524.png)


## T-Tests on Suspension Coils

![t_tests](https://user-images.githubusercontent.com/95188079/161436854-305027d7-6649-4b93-be7d-4dda39e0b9c8.png)


## Study Design: MechaCar vs Competition
- What metric or metrics are you going to test?  Given the current price of gas I would want to test fuel efficiency for city versus highway driving.
- What is the null hypothesis or alternative hypothesis?  Null hypothesis would be cars in the same class have the same fuel efficiency for city and highway driving.  The alternative hypothesis would be they are not the same.
- What statistical test would you use to test the hypothesis? And why?  I would run T and Anova tests to analyze the data.
- What data is needed to run the statistical test?  Fuel efficiency data for city and highway driving from a sample of cars across each class.
