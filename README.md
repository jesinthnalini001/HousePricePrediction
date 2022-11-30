# Project Name
> Outline a brief description of your project.

Business Objectives:
We need to model the price of houses with the available independent variables.


This model will then be used by the management to understand how exactly the prices vary with the variables. They can accordingly manipulate the strategy of the firm and concentrate on areas that will yield high returns. Further, the model will be a good way for management to understand the pricing dynamics of a new market.

## Table of Contents
* [General Info](#general-information)
You are required to model the price of houses with the available independent variables. This model will then be used by the management to understand how exactly the prices vary with the variables. They can accordingly manipulate the strategy of the firm and concentrate on areas that will yield high returns. Further, the model will be a good way for management to understand the pricing dynamics of a new market.
* [Technologies Used](#technologies-used)
Recursive Feature Elimination. Ridge and Lasso regularisation Techniques
* [Conclusions](#conclusions)

Compared to Ridge the model performance by Lasso Regression was better in terms of R2 values of Train and Test. Also it is better to use Lasso, as it brings a zero value to insignificant features which allow us to choose the predictive variables.

Surprise Housing firm has to keep a check on the predictors affecting the price of house. The higher values of positive coeeficients suggest a high sale value. Some of those features are:

MSZONING (Zoning classification)
OverallQual (overall material and finish of the house)
GrLivArea (grade above living area square feet)
OverallCond (overall condition of the house)
TotalBsmtSF / BsmtFinSF1 (Total basement area in square feet and the Basement finished square feet area)
* [Acknowledgements](#acknowledgements)

<!-- You can include any other section that is pertinent to your problem -->

## General Information
- Provide general information about your project here.

- What is the background of your project? To predict the house price based on the feature available
- What is the business probem that your project is trying to solve?
You are required to model the price of houses with the available independent variables. This model will then be used by the management to understand how exactly the prices vary with the variables. They can accordingly manipulate the strategy of the firm and concentrate on areas that will yield high returns. Further, the model will be a good way for management to understand the pricing dynamics of a new market.
- What is the dataset that is being used? House price data set with more than 100+ features

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->

## Conclusions
- Conclusion 1 from the analysis
Compared to Ridge the model performance by Lasso Regression was better in terms of R2 values of Train and Test. Also it is better to use Lasso, as it brings a zero value to insignificant features which allow us to choose the predictive variables.
- Conclusion 2 from the analysis
The optimal lambda value are:

Ridge - 8
Lasso - 0.0001

The Root Mean Squared error (RMSE):

Ridge - 0.125791
Lasso - 0.125515
- Conclusion 3 from the analysis
Surprise Housing firm has to keep a check on the predictors affecting the price of house. The higher values of positive coeeficients suggest a high sale value. Some of those features are:

MSZONING (Zoning classification)
OverallQual (overall material and finish of the house)
GrLivArea (grade above living area square feet)
OverallCond (overall condition of the house)
TotalBsmtSF / BsmtFinSF1 (Total basement area in square feet and the Basement finished square feet area)
- Conclusion 4 from the analysis

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->


## Technologies Used
- library - version 1.0
- library - version 2.0
- library - version 3.0

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