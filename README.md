# Linear regression Assignment - Bike Sharing

## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)
* [Acknowledgements](#acknowledgements)

<!-- You can include any other section that is pertinent to your problem -->

## General Information
A bike-sharing system in which bikes are made available for shared use to individuals on a short term basis for a price or free. It allow people to borrow a bike from a "dock" which is usually computer-controlled wherein the user enters the payment information, and the system unlocks it. This bike can then be returned to another dock belonging to the same system.

The objective is to model the demand for shared bikes with the available independent variables. It will be used by the management to understand how exactly the demands vary with different features. They can accordingly manipulate the business strategy to meet the demand levels and meet the customer's expectations. Further, the model will be a good way for management to understand the demand dynamics of a new market.

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->

## Conclusions
The following are the significant variables for predicting the demand for shared bikes
- temp
- yr
- windspeed
- seasons summer, winter
- weathersit of mist and lightsnow 
- mnth_sep
 we can draw the conclusions as below
 
- Rentals are increasing year on year. We can expect increase in rentals going forward in subsequent years
- If temperatures are high, there is increase in rentals. Supply needs to be there to meet the demand
- If weathersit is Mist and lightsnow, we can expect decrease in bike rentals. Company can plan accordingly
- If windspeed is high, there is decrease in demand for bikes. Company can reduce the inventory
- In seasons summer and winter have positive impact on bike rentals
- September month have higher impact comparatively to other months. Company can increase the stock to meet the demand

Model has below R2 on test and training sets
- Train dataset Adjusted R^2 : 0.824    
- Test dataset Adjusted R^2  : 0.79


<!-- You don't have to answer all the questions - just the ones relevant to your project. -->


## Technologies Used
- Language: Python
- Libraries: Scikit Learn, Pandas, Seaborn, Matplotlib
- Functions: MinMaxScaler, LinearRegression, RFE, OLS
<!-- As the libraries versions keep on changing, it is recommended to mention the version of library used in this project -->

## Acknowledgements
- This project was assigned by Upgrad for learning purposes


## Contact
Created by sunnihith srivatsav


<!-- Optional -->
<!-- ## License -->
<!-- This project is open source and available under the [... License](). -->

<!-- You don't have to include all sections - just the one's relevant to your project -->
