# Bike Sharing Assignment
> BoomBikes has decided to come up with a mindful business plan to be able to accelerate its revenue as soon as the ongoing lockdown comes to an end, and the economy restores to a healthy state. They want to understand the factors affecting the demand for these shared bikes in the American market.
- Which variables are significant in predicting the demand for shared bikes
- How well those variables describe the bike demands


## Table of Contents
* [General Info](#general-information)
* [Conclusions](#conclusions)
* [Steps Followed](#steps-followed)


<!-- You can include any other section that is pertinent to your problem -->

## General Information
> A bike-sharing system is a service in which bikes are made available for shared use to individuals on a short term basis for a price or free  US bike-sharing provider. BoomBikes has recently suffered considerable dips in their revenues due to the ongoing Corona pandemic. The company is finding it very difficult to sustain in the current market scenario. So, it has decided to  to accelerate its revenue as soon as the economy restores to a healthy state.

> A Linear regression model is required to be performed with the available independent variables. It will be used by the management to understand how exactly the demands vary with different features. They can accordingly manipulate the business strategy to meet the demand levels and meet the customer's expectations. Further, the model will be a good way for management to understand the demand dynamics of a new market. 

> Based on various meteorological surveys and people's styles, the service provider firm has gathered a large dataset on daily bike demands across the American market based on some factors. 

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->

## Steps Followed
- Analysing the Data and Data Visualization
- Data Cleaning and Data Manipulation
- Creating dummy variables
- Train-Test split
- Rescaling of Data
- Building the model
- Model Interpretation
- Assumptions
- Predictions
- Model Evaluation

## Conclusions
These five variables which are probale factor based on the Linear Regression model which are impacting the demand of Bike sharing -
- temp -a unit increase in temp increases the bike sharing by 0.57 units
- weathersit_3(Light Snow, Light Rain + Thunderstorm + Scattered clouds, Light Rain + Scattered clouds)   -a unit increase in weathersit_3 decreases the bike sharing by 0.30 units
- yr - a unit increase in year increases the bike sharing by 0.230846 units
- windspeed -a unit increase in windspeed decreases the bike sharing by 0.155191 units
- season_4(winter) -a unit increase in season_4 increases the bike sharing by 0.128744 units

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->



<!-- Optional -->
<!-- ## License -->
<!-- This project is open source and available under the [... License](). -->

<!-- You don't have to include all sections - just the one's relevant to your project -->
