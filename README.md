# Linear Regression Assignment (Bike-sharing system)
> It is a service in which bikes are made available for shared use to individuals on a short term basis for a price or free.
> Many bike share systems allow people to borrow a bike from a "dock" which is usually computer-controlled wherein the user enters the payment information, and the system unlocks it. This bike can then be returned to another dock belonging to the same system.


## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)
* [Acknowledgements](#acknowledgements)

<!-- You can include any other section that is pertinent to your problem -->

## General Information
- BoomBikes (US bike-sharing provider)
	- The company wants to know:
		- Which variables are significant in predicting the demand for shared bikes?
		- How well those variables describe the bike demands?
- Business Goal
	- You are required to model the demand for shared bikes with the available independent variables. It will be used by the management to understand how exactly the demands vary with different features. They can accordingly manipulate the business strategy to meet the demand levels and meet the customer's expectations. Further, the model will be a good way for management to understand the demand dynamics of a new market.

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->

## Conclusions
- Bike renting is high in season summer and fall.
- Bike renting is high in month May-Oct.
- Bike renting is high on Sat, Wed, Thu, Fri.
- Bike renting is high in clear weather.
- Bike renting is high in year 2019.
- Bike renting is high in working days and if there is no holiday
- Registered count is increasing every month

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->


## Technologies Used
- Numpy
- python
- Pandas

<!-- As the libraries versions keep on changing, it is recommended to mention the version of library used in this project -->

## Acknowledgements
- The R-squared value of the train set is 80.88 whereas the test set has a value of 82.16 which suggests that our model broadly explains the variance quite accurately on the test set and thus we can conclude that it is a good model.
- Our developed model's mean squared error is almost 0 on both the training and testing datasets which suggests that the variance is accurately predicted on the test set. The p-values and VIF were used to select the significant variables.
- We can conclude that the bike demands for the BoomBikes is company is dependent on the temperature and whether it is a workingday or not.
- Additionally more sales was on the summer and fall season. We had observed that the months of May-October had higher use of rentals. In terms of days the maximum focus was on days like Wed, Thurs and Sat and Fri.
- These interpretations help us derive meaningful insights in the bike rental market and the behaviour of the people. One of the recommendations based on this model are that there should be aggressive marketing in the summer and spring season to drive up rentals. Since the summer months also show low rental levels.


## Contact
Created by [@Code-with-Karan1606] - feel free to contact me!


<!-- Optional -->
<!-- ## License -->
<!-- This project is open source and available under the [... License](). -->

<!-- You don't have to include all sections - just the one's relevant to your project -->