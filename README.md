# Housing Price Prediction using Advanced Regression
> The main objective of this project is to build a model predict the Housing Sale Prices of the properties in Australia based on the available features


## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)


## General Information

- To understand the important variables affecting the sale price
- To use advanced regression (Lasso and Ridge) to solve the business problem
- Public dataset from SurpriseHousing was used

## Conclusions
#### Conclusions -
- Data was cleaned and prepared, features were selected through RFE by coarse tuning and through VIF and p-values by fine tuning<br>
- Optimal value of lambda for lasso is 20 and for ridge it is 70<br>
- Advanced Regression : Ridge regression seemed to perform better than lasso with a train R-square of 0.83 & test R-square value of 0.85<br> 
- The important variables for the prediction of sales price of houses are:<br>
1. OverallQual
2. GrLivArea
3. Neighbourhood
4. YearBuilt   
5. GarageCars
6. MsSubClass        
7. BsmtQual       

## Technologies Used
- Pandas - version 1.3.4
- Matplotlib - version 3.4.3
- Seaborn - version 0.11.2
- Numpy - version 1.20.3
- Sklearn - version 0.24.2
- Statsmodels - version 0.12.2

## Contact
Created by [@karthickchetti] - feel free to contact me!