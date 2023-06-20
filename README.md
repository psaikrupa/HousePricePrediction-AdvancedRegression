# Linear Regression Programming Assignment - Bike Sharing System

## Table of Contents
* [Problem Statement](#problem-statement)
* [Business Goal](#business-goal)
* [Conclusions](#conclusions)
* [Acknowledgements](#acknowledgements)

<!-- You can include any other section that is pertinent to your problem -->

## Problem Statement
A bike-sharing system is a service in which bikes are made available for shared use to individuals on a short term basis for a price or free. Many bike share systems allow people to borrow a bike from a "dock" which is usually computer-controlled wherein the user enters the payment information, and the system unlocks it. This bike can then be returned to another dock belonging to the same system.


A US bike-sharing provider BoomBikes has recently suffered considerable dips in their revenues due to the ongoing Corona pandemic. The company is finding it very difficult to sustain in the current market scenario. So, it has decided to come up with a mindful business plan to be able to accelerate its revenue as soon as the ongoing lockdown comes to an end, and the economy restores to a healthy state. 


In such an attempt, BoomBikes aspires to understand the demand for shared bikes among the people after this ongoing quarantine situation ends across the nation due to Covid-19. They have planned this to prepare themselves to cater to the people's needs once the situation gets better all around and stand out from other service providers and make huge profits.


They have contracted a consulting company to understand the factors on which the demand for these shared bikes depends. Specifically, they want to understand the factors affecting the demand for these shared bikes in the American market. The company wants to know:

Which variables are significant in predicting the demand for shared bikes.
How well those variables describe the bike demands
Based on various meteorological surveys and people's styles, the service provider firm has gathered a large dataset on daily bike demands across the American market based on some factors. 
<!-- You don't have to answer all the questions - just the ones relevant to your project. -->

## Business Goal
Business Goal is to model the demand for shared bikes with the available independent variables. It will be used by the management to understand how exactly the demands vary with different features. They can accordingly manipulate the business strategy to meet the demand levels and meet the customer's expectations. Further, the model will be a good way for management to understand the demand dynamics of a new market. 

## Conclusions

The Adjusted R2 Score of the train data is 0.774 or 77.4%
The Adjusted R2 Score of the test data is 0.714 or 71.4%

*Best Fitter Line Equation*

Best fitted Line - cnt = yr * 0.2477 + holiday * -0.0888 + windspeed * -0.1677 + 03-Mar * 0.0528 + 05-May * 0.0746 + 06-Jun * 0.0975 + 08-Aug * 0.1003 + 09-Sep * 0.1373 + Spring * -0.2324 + LihtRain * -0.2893 + Mist * -0.0946

*Feature Summary*
1) Year - With evey passing year, the demand is growing for bike rental. This coefficient of yr feature is 0.2477. This signifies that the demand is expected to increast by 0.2477 with a unit increase in the yr value.
2) Weather Situation - LightRain features depict a negative coefficient (-0.2893) suggesting that a demand is expected to decrease with an increase in unit value of these features. So, we can expect that the demand will decrease when there is light rain.
3) Season - Sprint feature - has a negative coefficient (-0.2324) suggesting that the demand is expected to decrease when it is spring.
4) WindSpeed - windspeed has a negative coefficient (-0.1677) suggesting that the demand is expected to decrease with increase in windspeed

## Contact
p.saikrupa@gmail.com


<!-- Optional -->
<!-- ## License -->
<!-- This project is open source and available under the [... License](). -->

<!-- You don't have to include all sections - just the one's relevant to your project -->
