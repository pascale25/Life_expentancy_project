# Life_expentancy_project

## Factors Driving Life Expectancy : Does immunization matters?

In view of the current pandemic, vaccination does not seem to find the consent of some people in the world. A look at the impact of vaccination on life expectancy could be important to highlight.

 So, does immunization matter?

The dataset (life expectancy, health factors for 193 countries)  2000-2015.

 The predicting variables were then divided into several broad categories:​
Immunization related factors, 
Mortality factors, 
Economical factors, 
and Social factors!

The present project assessed the contribution and the relationship of each feature on life expectancy with a special focus on immunization factors,  and develop a model to predict life expectancy.  

### How does the distribution of life expectancy look like?


![image](https://user-images.githubusercontent.com/90922607/157615572-b7a634bd-0e2a-4251-88d6-b752cbe9265a.png)


### How was the life expectancy over one decade (2005 to 2015) ?


![image](https://user-images.githubusercontent.com/90922607/157615718-9e289690-71c9-44e1-a408-cb2b00ffda23.png)

### Immunization and life expectancy

![image](https://user-images.githubusercontent.com/90922607/157616929-60072953-75a0-491c-a1ea-851d19c0cf83.png)

![image](https://user-images.githubusercontent.com/90922607/157616965-61235cae-524e-4833-897d-45d5e93742a8.png)

![image](https://user-images.githubusercontent.com/90922607/157617001-165fe804-8e6d-49fe-b0a1-a801acb53a11.png)


### key outcomes 

Life expectancy has increased over years in both developed and developing countries

The mean average of the life expectancy of developed countries is generally higher compared to  that of developing countries
However, the ratio of LE over the decade of 2005 to 2015 showed that life expectancy in developing countries has greatly increased.

It has been highlighted that immunization has impacted the improvement of life expectancy in a developing country, as well as the reduction in infant deaths.

The analysis revealed that economic factors play an important role in the system, it is why countries with higher income resources and GDP tend to have high life expectancy even if the population is big. In developing countries, an increase in the population tends to impact negatively life expectancy.

Many (14) regression models have been developed to predict expectancy, the chosen one is Gradient boost with MAE of 0.202 on train set and 1.431 on the test set, R square is 0.94 on the test set.

