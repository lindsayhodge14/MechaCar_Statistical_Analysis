# MechaCar_Statistical_Analysis
Learning R

## Deliverable 1
![Deliverable_1_lm.png](/Resources/Deliverable_1_lm.png)
![Deliverable_1_summary.png](/Resources/Deliverable_1_summary.png)

Question 1: The intercept coefficient and the vehicle_length and ground_clearance variables all appear to provide a non-random amount of variance to the mpg values in the dataset.

Question 2: Given a p-value of roughly .00, I reject the null hypothesis which states the slope is equal to zero; thereby, accepting the alternative hypothesis which states that the slope is not equal to zero. 

Question 3: The adjusted r-squared statistic of .68 indicates that the linear model effectively predicts the mpg with moderate strength. 

## Deliverable 2
### Summary Statistics on Suspension Coils
![Deliverable_2_total_summary.png](/Resources/Deliverable_2_total_summary.png)
![Deliverable_2_lot_summary.png](/Resources/Deliverable_2_lot_summary.png)

Upon reviewing the total statistical summary of the suspension coils contained within the various manufacturer lots, one would note that the design specifications which requires the variance of the suspension coils to not exceed 100 lbs per square inch has been met given the data's total variance equals approximately 62. However, if the lots are assessed seperately, Lot 3 has the potential to not meet design specifications given its variance is approximately 170.

## Deliverable 3
![Deliverable_3_step_1.png](/Resources/Deliverable_3_step_1.png)
![Deliverable_3_Lot1.png](/Resources/Deliverable_3_Lot1.png)
![Deliverable_3_Lot2.png](/Resources/Deliverable_3_Lot2.png)
![Deliverable_3_Lot3.png](/Resources/Deliverable_3_Lot3.png)

### T-test on Suspension Coils
Overall: With 95% confidence, I fail to reject the null hypothesis which states that the true mean of the dataset is equal to 1500. Despite failing to reject the null and presuming that the sample mean equates to the population mean, it is important to acknowledge the small margin by which I elected to reject the null. It is likely that minimal adjustments to the data or the loss/addition of a variable would lower the p-value enough to exhibit that the sample mean does not equate to the population mean.

Lot 1: With 99% confidence, I fail to reject the null hypothesis which states that the true mean of the dataset is equal to 1500. Given a p-value of 1, the Lot 1 sample data is suggested to reflect the population data.

Lot 2: With With 95% confidence, I fail to reject the null hypothesis which states that the true mean of the dataset is equal to 1500. A .60 p-value confirms that the Lot 2 data is also reflective of the population data; however, not as precisely as the Lot 1. 

Lot 3: Given a p-value of .04, with 95% confidence, I reject the null hypothesis which states that the true mean of the dataset is equal to 1500. The alternative hypothesis which states that the true mean of the dataset is not equal to 1500 is accepted. Lot 3 sample data is not reflective of the population and should not be depended upon for inquiries related to suspension coils.

## Deliverable 4
### Study Design: MechaCar v.s. Competition
To quantify how MechaCar performs against competition, I would expand the completed multiple linear regression to include the following dependent variables... 
* safety data
* average number of repairs or maintenance costs
* average number of manufacturer recalls
* electric/hybrid addition: as a boolean

Additionally, I would change the independent variable to cost to ensure that the pricing of MechaCar's vehicles is affordable and able to beat out competitors in a particular subset/portion of the market. 
