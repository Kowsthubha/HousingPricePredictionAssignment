# HousingPricePredictionAssignment
> A US-based housing company has decided to enter the Australian market. As part of this the company is looking at prospective properties to buy to enter the market. We are expected to build a regerssion model using regularization in order to predict the actual value of the prospective properties and decide whether to invest in or not


## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)
* [Acknowledgements](#acknowledgements)

<!-- You can include any other section that is pertinent to your problem -->

## General Information
- The company is looking out for different parameters/properties influences the price of the house and to purchase house at a price below actual value
- The US-based housing compnay named Surprise Housing has decided to enter the Austrlian market
- You are required to model the price of houses with the available independent variables. This model will be used by the management to understand how exactly the prices vary with the variables. Accordingly the comapany comes out with the high yield returns strategy
- the company has collected a data set from the sale of houses in Australia

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->

## Conclusions
The variables significant in predicting the price of a house are:-

> GrLivArea, OverallQual_9, OverallCond_9, OverallQual_8, Neighborhood_Crawfor, Functional_Typ, Exterior1st_BrkFace, SaleCondition_Alloca, CentralAir_Y, TotalBsmtSF, Neighborhood_Somerst, TotalBsmtSF and Condition1_Norm

Here will see only top few variables

* GrLivArea:an increase of 1 square foot of house area above ground, the price will increase by 1.09 to 1.11 times
* OverallQual_9 & OverallQual_8: if the overall material and finish of the house is Very Good or Excellent, the price of house will increase by 1.08 to 1.13 times
* Neighborhood_Crawfor: if Crawford is a nearby location, then the price of house will increase by 1.07 to 1.09 times
* Functional_Typ: if the home functionality is typical, then the price of house will increase by 1.07 to 1.08 times
* Exterior1st_BrkFace: if the exterior covering on the house is Brick Face, the price of house will increase by 1.07 to 1.08 times.

In a similar manner, we can deduct how well each variable describes the price of a house.

> Optimal value of lambda for Ridge Regression = 10

> Optimal value of lambda for Lasso = 0.001

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->


## Technologies Used
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Regression

<!-- As the libraries versions keep on changing, it is recommended to mention the version of library used in this project -->

## Acknowledgements
Give credit here.
- This project was inspired by...
- References if any...
- This project was based on [this tutorial](https://www.example.com).


## Contact
Created by [@githubusername] - feel free to contact me!


<!-- Optional -->
<!-- ## License -->
<!-- This project is open source and available under the [... License](). -->

<!-- You don't have to include all sections - just the one's relevant to your project -->
