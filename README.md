# Project Name
> Advanced Regression Case study - Surprise Housing


## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)
* [Acknowledgements](#acknowledgements)

<!-- You can include any other section that is pertinent to your problem -->

## General Information
A US-based housing company named Surprise Housing has decided to enter the Australian market. The company uses data analytics to purchase houses at a price below their actual values and flip them on at a higher price. For the same purpose, the company has collected a data set from the sale of houses in Australia. The data is provided in the CSV file below.

The company is looking at prospective properties to buy to enter the market. You are required to build a regression model using regularisation in order to predict the actual value of the prospective properties and decide whether to invest in them or not.

The company wants to know:

* Which variables are significant in predicting the price of a house, and

* How well those variables describe the price of a house.

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->

## Conclusions
1. The variables significant in predicting the price of house are:<br />
    * **GrLivArea** - Above grade (ground) living area square feet.<br />
             Higher the house from ground, higher the price<br />
    * **OverallQual** - overall material and finish of the house is 8(Very good) & 9 (Excellent)<br />
            The price range increased from 1.07 to 1.13 for Qaulity of 8 and 9 material.<br />
    * **Neighborhood** - Crawford neighborhood attracts more pricing. Somerset neighborhood also contributes to high pricing to certain extent.<br />
            The price increases around 1.07 to 1.09 times if it is around Crawford<br />
    * **Exterior1st** - Ifthe Exterior covering of the house is Brick Face(BrkFace) the pricing will be more compared to other types of exterior.<br />
    * **Functional** - A typical home funcionality is more pricey as compared to other.<br />
            Price may increase by 1.07 for TYP functional type.<br />
    * **CentralAir** - Centrally air conditioned house attract more price.<br />
    * **TotalBsmtSF** - House with more basement area has more price.<br />
2. The optimal value for Lambda in *`Ridge Regression`* is *`10`* and for *`Lasso`* is *`0.001`*

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->


## Technologies Used
* numpy
* pandas
* matplotlib
* seaborn
* sklearn
* statsmodels
<!-- As the libraries versions keep on changing, it is recommended to mention the version of library used in this project -->

## Contact
- Parth Gandhi : 
> [![View on GitHub](https://img.shields.io/badge/GitHub-View_on_GitHub-blue?logo=GitHub)](https://github.com/Parth6288)

Please feel free to contact me

<!-- Optional -->
<!-- ## License -->
<!-- This project is open source and available under the [... License](). -->

<!-- You don't have to include all sections - just the one's relevant to your project -->