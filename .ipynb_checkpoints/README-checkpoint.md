# Bike Sharing Assignment
> build a multiple linear regression model for the prediction of demand for shared bikes


## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)
* [Acknowledgements](#acknowledgements)

<!-- You can include any other section that is pertinent to your problem -->

## General Information
> What is the background of your project?

To build a multiple linear regression model for the prediction of demand for shared bikes. A US bike-sharing provider BoomBikes has recently suffered considerable dips in their revenues due to the ongoing Corona pandemic.BoomBikes aspires to understand the demand for shared bikes among the people after this ongoing quarantine situation ends across the nation due to Covid-19.

Specifically, the company wants to understand the factors affecting the demand for these shared bikes in the American market.
> What is the business probem that project is trying to solve?

The company wants to know:
Which variables are significant in predicting the demand for shared bikes.
How well those variables describe the bike demands

> Business Goal

To build a model that captures the demand for shared bikes using the available independent variables.
The model can be used by the management to understand how exactly the demands vary with different features.
It can also be used by management to understand the demand dynamics of a new market.

> What is the dataset that is being used?

Boombikes company data from year 2018,2019

## Conclusions
Top 3 features contributing significantly towards explaining the demand of the shared bikes
1. temp(temperature) : Bikes were rented maximum when temperature was between 9-12 in all seasons. So company should boost their service when temperature is more than 9 degree celsius regardless of season
2. yr(year): Number of bike rentals has increased in 2019 compared to 2018 which is a good sign for Boombikes as bike renting trend is showing up curve
3. season , since september month has good postive coefficient,which is beginning of fall season in US



## Technologies Used
- sklearn
- matplotlib
- seaborn
- statsmodel

<!-- As the libraries versions keep on changing, it is recommended to mention the version of library used in this project -->


## Contact
Created by [https://github.com/Mahalakshmi-Totad] - feel free to contact me!


<!-- Optional -->
<!-- ## License -->
<!-- This project is open source and available under the [... License](). -->

<!-- You don't have to include all sections - just the one's relevant to your project -->