# Project_Car_Fuel_Consumption

My research question is about the factors can cause the fuel consumption for the specific car (same car, not to compare different cars). The result of this research question is that the fuel/gas type causes the fuel consumption mostly. E10, the ethanol-based fuel, has lower consumption than SP98 does. The suggestion based on the finding is that filling more E10 since it has lower fuel consumption, lower cost, and cleaner than other fuel types. Filling E10 also helps on saving our planet :) 

# Research Questions
1. What factors may affect the car fuel consumption?
2. Is the weather one of the factors?
3. Can fuel type affect the consumption?
4. Can speed affect the fuel consumption?

These research questions help me to build up the thoughts on how to deal with this project and the dataset that I need to look for. To the reader, they will be clear about my thoughts at the beginning stage of this project with reading these questions.

# Data Questions 

1. What datasets do I need to use to answer the questions?

The datasets that include the information of the following:
1. Distance
2. Speed
3. Temperature
4. AC used or not
5. Gas type
6. Weather condition

The metrics list above can help to figure out what causes the car fuel consumption. Since the data in this dataset are all the numbers, I can use them directly from the dataset. I used the regression method in Excel to find is there any factor can cause the fuel consumption obviously. However, regression did not work that well for this dataset. So I rearranged the data about the total distance within two refills and the average consumption within two refills. Then, I found that the fuel type causes the consumption, and SP98 cost more than E10 on consumption.

# I found the dataset on Kaggle, data source: https://www.kaggle.com/anderas/car-consume

# The steps/plan to accomplish my data analysis:
1. Find all the datasets needed and put them together on a same sheet.
2. Compare one of the metrics each time with consumption by using the regression in Excel to see what factor affect the fuel consumption mostly.
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
