# Bike Sharing System 
> A Multiple Linear Regression Model


## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)
* [Acknowledgements](#acknowledgements)


## General Information
A bike-sharing system is a service in which bikes are made available for shared use to individuals on a short term basis for a price or free. Many bike share systems allow people to borrow a bike from a "dock" which is usually computer-controlled wherein the user enters the payment information, and the system unlocks it. This bike can then be returned to another dock belonging to the same system.


A US bike-sharing provider BoomBikes has recently suffered considerable dips in their revenues due to the ongoing Corona pandemic. The company is finding it very difficult to sustain in the current market scenario. So, it has decided to come up with a mindful business plan to be able to accelerate its revenue as soon as the ongoing lockdown comes to an end, and the economy restores to a healthy state. 


In such an attempt, BoomBikes aspires to understand the demand for shared bikes among the people after this ongoing quarantine situation ends across the nation due to Covid-19. They have planned this to prepare themselves to cater to the people's needs once the situation gets better all around and stand out from other service providers and make huge profits.


They have contracted a consulting company to understand the factors on which the demand for these shared bikes depends. Specifically, they want to understand the factors affecting the demand for these shared bikes in the American market. The company wants to know:

Which variables are significant in predicting the demand for shared bikes.
How well those variables describe the bike demands
Based on various meteorological surveys and people's styles, the service provider firm has gathered a large dataset on daily bike demands across the American market based on some factors. 


Business Goal:
You are required to model the demand for shared bikes with the available independent variables. It will be used by the management to understand how exactly the demands vary with different features. They can accordingly manipulate the business strategy to meet the demand levels and meet the customer's expectations. Further, the model will be a good way for management to understand the demand dynamics of a new market. 




## Conclusions
- The r2_score on the training dataset is 0.83 and the adjusted r2_score is 0.826 and for the test dataset is 0.0031. It is almost zero for the test dataset which implies that the model poorly fits on the test data.The first model is created using the manual feature selection by p values and VIF and I started working on the second model using RFE. As we can see the r2_score on the training dataset is 0.83 and for the test dataset is 0.83 and the adjusted r2_score is 0.826 while using RFE. Manual feature selection may lead to less r2_score in the test dataset eventhough the r2_score in the training dataset is 0.83.



## Technologies Used
- library - numpy, pandas, statsmodels, sklearn, warnings, seaborn, matplotlib



## Acknowledgements
Give credit here.
- References : StackOverflow


## Contact
Created by [@FalconSus11] - feel free to contact me!


