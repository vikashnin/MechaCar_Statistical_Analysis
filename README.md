# MechaCar_Statistical_Analysis

## Linear Regression to Predict MPG
Which variables/coefficients provided a non-random amount of variance to the mpg values in the dataset?
The variables/coefficients ground_clearance and vehicle_length provided a random amount of variance to the mpg values in the dataset. While, spoiler_angle and vehicle weight provided a non-random amount of variance. 
 
Is the slope of the linear model considered to be zero? Why or why not?
The slope is not considered to be zero, because the p-value is less than 0.05.

Does this linear model predict mpg of MechaCar prototypes effectively? Why or why not?
Yes, the linear model predict mpg of MechaCar protoypes effectively predicts the correct mpg values because our r-squared value was 0.71, which is about 70%.

## Summary Statisitics on Suspension Coils
### Total Summary
<img width="285" alt="Screen Shot 2022-05-22 at 10 49 46 PM" src="https://user-images.githubusercontent.com/98666231/169751972-f0f4038a-c9bb-4ed7-9efb-e5267998d9b1.png">

### Lot Summary
<img width="467" alt="Screen Shot 2022-05-22 at 10 49 25 PM" src="https://user-images.githubusercontent.com/98666231/169751929-db5cc005-9b52-4225-a78d-4ca9ccd60b46.png">

The design specifications for the MechaCar suspension coils dictate that the variance of the suspension coils must not exceed 100 pounds per square inch. Does the current manufacturing data meet this design specification for all manufacturing lots in total and each lot individually? Why or why not?

The variance for Lot 1 and Lot 2 meet the design specification. However, Lot 3 doesn not meet the specification because it exceed the manufacturing specifications.

## T-Tests on Suspension Coils
### T-Test for All Lots
<img width="423" alt="Screen Shot 2022-05-22 at 11 04 06 PM" src="https://user-images.githubusercontent.com/98666231/169753683-f496fd84-f214-4678-88a9-73adbfeba950.png">

### T-Test Lot 1
<img width="582" alt="Screen Shot 2022-05-22 at 11 04 35 PM" src="https://user-images.githubusercontent.com/98666231/169753744-83a5a653-7fcb-48b1-a9b7-f936b57c8732.png">

### T-Test Lot 2
<img width="574" alt="Screen Shot 2022-05-22 at 11 04 52 PM" src="https://user-images.githubusercontent.com/98666231/169753788-144c3688-9135-4bdb-bce8-999617fccbe0.png">

### T-Test Lot 3
<img width="587" alt="Screen Shot 2022-05-22 at 11 05 09 PM" src="https://user-images.githubusercontent.com/98666231/169753817-ba5ccba0-37b4-4eed-839a-b3ff67e91ae1.png">

Taking a look at the t-tests, Lot 1 and Lot 2 show a similary population mean. However, Lot 3 is significantly low. 

## Study Design: MechaCar vs Competition
There are many factor a consumer might consider when buying a car. For example, brand, gas, horsepower, maintenance and cost.

What metric or metrics are you going to test?
Due to the growing gas prices I would test horsepower, gas prices and fuel efficiency.

What is the null hypothesis or alternative hypothesis?
The null hypothesis is that the fuel efficieny is zero. The alternative hypothesis is that fuel efficiency is not zero.

What statistical test would you use to test the hypothesis? And why?
A bar chart would show the variables impact the fuel efficiency.

What data is needed to run the statistical test?
We need a random selection of car from both places and collect the data for gas and fuel efficiency. 

