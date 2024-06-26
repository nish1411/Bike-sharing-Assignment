# Lending Club Case Study
> This project involves analyzing bike-sharing data set to identify the variables affecting the demand of shared bikes. This assignment involves building a multiple linear regression model for the prediction of demand for shared bikes. The analysis uses Python and its data analysis libraries, focusing on Multiple linear Regression model using RFE analysis to understand the demand dynamics of a new market. 

<br>

>## Table of Contents
* [General Info](#general-information)
* [Approach](#Approach)
* [Analysis](#analysis-steps-and-observations)
* [Business Recommendations](#business-recommendations)
* [Conclusions](#conclusion)
* [Technologies Used](#technologies)
* [Files](#files-in-the-project)
* [Contributors](#contributors)

>## General Information
**Background:**
A bike-sharing system is a service in which bikes are made available for shared use to individuals on a short term basis for a price or free. Many bike share systems allow people to borrow a bike from a "dock" which is usually computer-controlled wherein the user enters the payment information, and the system unlocks it. This bike can then be returned to another dock belonging to the same system.

**Business Problem:**
A US bike-sharing provider BoomBikes has recently suffered considerable dips in their revenues due to the ongoing Corona pandemic. The company is finding it very difficult to sustain in the current market scenario. So, it has decided to come up with a mindful business plan to be able to accelerate its revenue as soon as the ongoing lockdown comes to an end, and the economy restores to a healthy state. 

**Business Objective:**
In such an attempt, BoomBikes aspires to understand the demand for shared bikes among the people after this ongoing quarantine situation ends across the nation due to Covid-19. They have planned this to prepare themselves to cater to the people's needs once the situation gets better all around and stand out from other service providers and make huge profits.

They have contracted a consulting company to understand the factors on which the demand for these shared bikes depends. Specifically, they want to understand the factors affecting the demand for these shared bikes in the American market. The company wants to know:

- Which variables are significant in predicting the demand for shared bikes.
- How well those variables describe the bike demands

**Dataset Used:**
Bike Sharing dataset on daily bike demands across the American market through the time period 2018 t0 2019 is provided.

>## Approach
 - Perform EDA of the data to visualize and understand the data
 - Build a multiple linear regression model using RFE + Manual approach using statsmodel and sklearn libraries
 

> ## Technologies
- Jupyter Notebook version:  6.5.4
- Python version:  3.11.5 
- Pandas version:  2.0.3
- NumPy version:  1.24.3
- Matplotlib version:  3.7.2
- Seaborn version:  0.12.2
- Statsmodels version: 0.14.0
- Scikit-learn version: 1.3.0
 

## Conclusion
Significant variables to predict the demand for shared bikes

- year
- holiday
- workingday
- temp
- season_spring
- season_summer
- season_winter
- month_Sept  
- weather_Light_Rain 
- weather_Misty   


> ## Contributors
- Nishant Singh

