# House Price Prediction Assignment
> Project by Upgrad (Third Upgrad Assignment) <br>
>
> This project uses Regularisation to build a polynomial regression model for the prediction of the actual value of the prospective properties and decide whether to invest in them or not.
> - Which variables are significant in predicting the price of a house
> - How well the variables describe the price of a house
>
> The project contains:
> - The data set `train.csv`
> - The data dictionary `data_description.txt`
> - Answers to the Subjective Questions in pdf format `Truong_Nguyen_Manh.pdf`


## Table of Contents
* [General Information](#general-information)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)
* [Contact](#contact)



- **Business problem:**
Aim is to model the price of houses with the available independent variables. This model will then be used by the management to understand how exactly the prices vary with the variables. They can accordingly manipulate the strategy of the firm and concentrate on areas that will yield high returns. Further, the model will be a good way for management to understand the pricing dynamics of a new market.

## Assignment Steps performed in the notebook

## Data visualisations
- perform EDA to understand various variables
- check correlation between the variables 

## Data preparation
- clean the data structure
- drop unneccessary variables
- create dummy variables for all categorical features
- divide the data to train and test
- perform scaling
- divide data into dependent and independent variables

## Data modelling and evaluation
- create linear regression model with no Regularisation
- create models using Ridge and Lasso Regularisation

## Conclusions
1. `GrLivArea` is by far the most important predictor
2. The top variables are intuitive.
3. Lasso is the chosen model for the final model, because it creates a simple model with the top features.





## Technologies Used

![Python](https://img.shields.io/badge/Python-3.10-informational?style=flat&logoColor=white&color=2bbc8a)
![NumPy](https://img.shields.io/badge/NumPy-1.21.5-informational?style=flat&logoColor=white&color=2bbc8a)
![Pandas](https://img.shields.io/badge/Pandas-1.3.5-informational?style=flat&logoColor=white&color=2bbc8a)
![Matplotlib](https://img.shields.io/badge/Matplotlib-3.5.1-informational?style=flat&logoColor=white&color=2bbc8a)
![Seaborn](https://img.shields.io/badge/Seaborn-0.11.2-informational?style=flat&logoColor=white&color=2bbc8a)
![sklearn](https://img.shields.io/badge/Sklearn-1.0.2-informational?style=flat&logoColor=white&color=2bbc8a)
![statsmodels](https://img.shields.io/badge/statsmodels-0.13.1-informational?style=flat&logoColor=white&color=2bbc8a)
![scipy](https://img.shields.io/badge/scipy-1.8.0-informational?style=flat&logoColor=white&color=2bbc8a)



## Contact
Created by Truong Nguyen Manh - feel free to contact me! <br>

