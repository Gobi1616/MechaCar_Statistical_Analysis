# MechaCar_Statistical_Analysis

## Project Overview

This project involves the use of statistics and hypothesis testing to analyze a series of datasets from the automotive industry.
All of the statistical analysis and visualizations is written in the R programming language.

## Resources

Data Source: MechaCar_mpg.csv, Suspension_Coil.csv
Software: RStudio Version 1.4.1717

## Linear Regression to Predict MPG

![image](https://user-images.githubusercontent.com/82549869/128638892-d64f526b-6a8c-4aa3-9e3c-a916441745ab.png)

- R-square is 0.71 so 71% of the variations in mpg can be explained by changes in the vehicle length, the vehicle weight, the spoiler angle, the drivetrain and the ground clearance. We can consider this linear model as fairly efficient to predict mpg of MechaCar prototypes.
- Vehicle length and ground clearance (and Intercept) add a non-random amount of variance to the linear model of mpg, according to our findings.

## Summary Statistics on Suspension Coils

![image](https://user-images.githubusercontent.com/82549869/128639216-22f9aa9a-8b10-41d1-a7b1-03edba771b8a.png) 
                    
![image](https://user-images.githubusercontent.com/82549869/128639225-17cb2d24-5467-4b91-85d4-21529b2bd6bb.png)
                     
- The MechaCar suspension coils must not have a deviation of more than 100 pounds per square inch, according to the design specifications.
- With a global variance of 62.3 psi, the design parameters are followed for all production lots.
- Lot 1 and Lot 2 are both within specs, with variations of 0.98 and 7.5 psi, respectively. Lot 3 is out of specification, with a variation of

## T-Tests on Suspension Coils

### T-Test all manufacturing lots against the population mean

![image](https://user-images.githubusercontent.com/82549869/128639238-9dc24c81-91af-4d69-af61-34706184019d.png)
                    
### T-Tests each manufacturing lot against the population mean

![image](https://user-images.githubusercontent.com/82549869/128639275-733cf017-37f0-493f-9a9e-c0d33acaec57.png)
                    
![image](https://user-images.githubusercontent.com/82549869/128639290-6eade2c9-ed5b-4c5f-a662-47f8d0caecac.png)
                    
![image](https://user-images.githubusercontent.com/82549869/128639304-2a7f4d04-14f3-4ba7-ad54-5b4b95148631.png)

## Summary

The null hypothesis in this situation would be that all performance measures for the MechaCar prototype and all vehicles from other manufacturers are statistically similar. A one-way ANOVA test would be used. This test compares the means of a continuous numerical variable across a group of people. We would compare the means of each statistic across the different manufacturers in this analysis.

