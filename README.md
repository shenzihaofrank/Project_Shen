# Project_Car_Fuel_Consumption
# Questions in general
1. What factors may affect the car fuel consumption?
2. Is the weather one of the factors?
3. Can fuel type affect the consumption?
4. Can speed affect the fuel consumption?

# What datasets do I need to answer the questions?
The datasets that include the information of the following:
1. Distance
2. Speed
3. Temperature
4. AC used or not
5. Gas type
6. Weather condition

# The metrics list above can help to figure out the car fuel consumption.
# Data source: https://www.kaggle.com/anderas/car-consume

# The steps/plan to accomplish my data analysis:
1. Find all the datasets needed and put them together on a same sheet.
2. Compare two of the metrics each time to see what metrics affect the fuel consumption most.
3. Data visualizations - make graphs or charts to show the relationship of each factor and to find out which factor causes the fuel consumption mostly.
(I will control the variates to show the effect of fuel consumption when one of the factor is changed.)

# Data Answers
### Analyzing the factors to figure out which affect the car fuel consumption mostly. 

### The chart below shows the data of consumption and speed from the dataset. However, since there are so many data, it is hard to see the influence of speed to fuel consumption. So I need to try other ways to figure out the reason that really affect the fuel consumption.
![Alt text](https://github.com/shenzihaofrank/Project_Shen/blob/master/Consumption%20vs%20Speed.PNG)


### The chart below shows the consumption per refill (between every two fills) for gas E10 and SP98. These two types of gas are filled in the car. I summarize all the refilling data and calculate the fuel consumption per refill of each type of gas for each time to make this chart. Since other factors are not really affect the fuel consumption, so I focus on the fuel type.
![Alt text](https://github.com/shenzihaofrank/Project_Shen/blob/master/Consumption%20per%20refill.PNG)


### The chart below shows the average fuel consumption of E10 and SP98. It is clear that the fuel consumption of E10 is lower than SP98's. So this chart gives an important information that the fuel type is the main reason to cause the fuel consumption. 
![Alt text](https://github.com/shenzihaofrank/Project_Shen/blob/master/Average%20consumption.PNG)
