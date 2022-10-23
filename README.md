# MechaCar_Statistical_Analysis

## Project Overview:

#### Deliverable 1: Linear Regression to Predict MPG

#### Deliverable 2: Summary Statistics on Suspension Coils

#### Deliverable 3: T-Test on Suspension Coils

#### Deliverable 4: Design Proposal a Study Comparing the MechaCar to the Competition


## Linear Regression to Predict MPG

![Lin_Reg](https://user-images.githubusercontent.com/109227896/197421672-a81c0f91-7e6c-42ad-9609-e91e16a6e861.png)

### Which variables/coefficients provided a non-random amount of variance to the MPG values in the dataset?

According to our results, vehicle length and ground clearance are statistically unlikely to provide random amounts of variance to the linear model. What this means is that vehicle length and ground clearance have a considerable impact on MPG.

### Is the slope of the linear model considered to be zero? Why or why not?

The slope of the linear model is not considered to be zero because there is a significant relationship between two independent variables, vehicle length and ground clearance, and the dependent variable - MPG.

### Does this linear model predict mpg of MechaCar prototypes effectively? Why or why not?

The Multiple R-squared value is 0.7149. Therefore, the model predicts MPG of MechaCar effectively at a rate of approximately 71%. 


## Summary Statistics on Suspension Coils

#### Total Summary

![tot_summary](https://user-images.githubusercontent.com/109227896/197421743-d439e4a5-7aad-4bf5-83f9-c5765b6e9a9b.png)


#### Lot Summary

![lot_summary](https://user-images.githubusercontent.com/109227896/197421777-97fc86e9-2922-4e76-8a31-70818099e23b.png)

### The design specifications for the MechaCar suspension coils dictate that the variance of the suspension coils must not exceed 100 pounds per square inch. Does the current manufacturing data meet this design specification for all manufacturing lots in total and each lot individually? Why or why not?

In this model, Lots 1 and 2 meet design specifications, having very close mean and median values, with variances of 0.9796 and 7.4694. However, Lot 3 has the most variance amongst the three, 170.286 and does not meet the manufacturing expectations.


## T-Tests on Suspension Coils

The statistical analysis of this section determined if all manufacturing lots and each individual lot are statistically different from the population mean of 1,500 pounds PSI (per square inch). To accomplish this, t-tests were used to compare all manufacturing lots against mean PSI of the population. As illustrated in the tables below, there is a 95 percent confidence interval across all manufacturing lots and the true mean is equal to 1498.78. In addition, the p-value is 0.06028, which indicates sufficient evidence to reject the null hypothesis has not been provided.

#### All Manufacturing Lots

![summary](https://user-images.githubusercontent.com/109227896/197422069-9d6532b0-93aa-4845-ac77-973208f4a218.png)

#### Lot 1

![lot_1](https://user-images.githubusercontent.com/109227896/197422126-5cad2d69-d483-4e53-8254-cde02203abd3.png)

#### Lot 2

![lot_2](https://user-images.githubusercontent.com/109227896/197422138-e26a9531-f87d-4ac8-afcd-1f797188aad3.png)

#### Lot 3

![lot_3](https://user-images.githubusercontent.com/109227896/197422147-90316913-d250-4d4f-ad59-bb649b8d9461.png)


## Study Design: MechaCar vs Competition
