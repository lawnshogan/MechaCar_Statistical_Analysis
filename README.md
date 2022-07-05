# MechaCar_Statistical_Analysis

# Deliverable 1: Linear Regression to Predict MPG 
1. Ground clearance and length of vehicle are likely to provide a variance to the model. Therefore the vehicles ground clearance and length have significant impact of mpg. Other variance can include the spoiler type and angle, AWD and vehicle weight.
2. P-Value: Much smaller than the significance level of 0.05%. This indicates there is sufficient evidence to reject our null hypothesis.
3. Our model has an r-squared value of 0.71 - 71% of all mpg predictions will be determined by this model. The multiple regression model does predict mpg of MechaCar prototypes effectively.
4. Removing vehicle weight, spoiler angle, and AWD - Predictability does decrease, but not drastically (r-squared value falls from 0.7149 to 0.674).


# Deliverable 2: Summary Statistics on Suspension Coils

- MechaCar suspension coils policy - Suspension coils cannot exceed 100 pounds per square inch (PSI). 
- When looking at the production lot, the variance of the coils is 62.29 PSI (must be below 100 PSI).
- Lot 1 (0.98 PSI) and Lot 2 (7.47 PSI) - Within the 100 PSI requirement 
- Lot 3 is showing variance in consistency & performance at 170.29 PSI.

# Deliverable 3: T-Test on Suspension Coils

1. Lot 1 sample has the true sample mean of 1500. With a p-Value of 1, clearly we cannot reject the null hypothesis
- There is no statistical difference between the sample mean and the population mean (1500).

2. Lot 2 has similar outcome, 1500.02 (p-Value of 0.61)
- There is no statistical difference between the sample mean and the population mean (1500).

3. Lot 3 - Not comparable to lot 1 & 2. 
- Sample mean = 1496.14
- p-Value = 0.04 (lower than significance level of 0.05)
- Reject the null hypothesis - Mean and the presumed population mean are not statistically different.

# Deliverable 4

## Study Design: MechaCar vs Competition

1. Metrics
- Major manufacturers data (past three years) for the following metrics:

### IV = Independent Variable
### DV = Dependant Variable

- Drive Package : IV
- MPG Efficiency: IV
- Safety Rating: IV
- Selling Price: DV
- Resale Value: IV
- Annual Ownership Maintenance Cost: IV
- Engine Type: IV


2. Hypothesis: Null and Alternative
Key factors are determined for MechaCar's genre:

Null Hypothesis (Ho): MechaCar is correctly priced based on performance of key factors.
Alternative Hypothesis (Ha): MechaCar is NOT correctly priced based on performance of key factors.

3. Statistical Tests
Multiple linear regression would be used to determine the factors that have the highest correlation/predictability with the list selling price.
