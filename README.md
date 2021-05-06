# Final-Project
Link for the data set
https://openei.org/doe-opendata/dataset/f6c9151f-3488-452e-a898-f4f607a025e8/resource/c19dba77-47f4-47f3-b2a0-e20c3297f8b3/download/industrialindicators.xls

# Data background
The project is trying to simulate the data about the energy intensity indicators in the U.S from 1949-2004
Energy intensity data and documenttation published by the U.S DOE's office of Energy Efficiency and Renewable Energy.
Energy intensity is defined as:amount of energy used in producing a given level of out or activity, or energy per unit of output. This is the energy intensity of the industrial sector, which is an end-use that consists of all facilities and equipment used for producing, processing. 

It has the Electricity and fuels used for different industries from 1977 to 2004. 
It use the industry group code in the excel file, i have to cage the code to words first.
The NAICS xxx is the industry group code. For example NAICS 312 is the Industries in the Beverage and Tobacco product manufacturing subsector manufacture beverages and tobacco products.

# Goal of the project
For the project, I want to find out how the different industries energy used change from the giving data, and how the electricity sales and lose in the past 70 years.
For the method, the first part I’m using is similar to the project1, using the FFT and no-linear regression to find the trace of the energy used.
The second part I’m going to use multiple linear regression and k-nearest neighbors’ algorithm to predict the electricity and fuels used for different industries in the future. I am going to use the model in scikit-learn (sklearn.linear_model and sklearn.neighbors) in python to solve the problem. 

# For the python coding:
The first part is import data and extract data from excel and prepare.
The second part is plot the data for electricity and fuels use for different industries. Which include the FFT and no-linear.. Which is similar to project1.
The third part is using the multiple linear regression and KNN method to predict that will the energy use for the industrial in the future.

# The new modules:
The I’m going to use is the scikit-learn to analysis and predict the data. The coding to import the model is:
  (from skearn.linear_model import LinearRegression) for multiple Linear regression
  (from sklearn.neighbors import KneighborsRegressor) for KNN 

# The mathematical methods:
The mathematical methods includes FFT, no-linear regression, multiple Linear regression and KNN.
The multiple linear regression is a statistical technique that uses several explanatory variables to predict the outcome of a response variable. The goal of multiple linear regression is to model the linear relationship between the explanatory (independent) variables and response (dependent) variable.
The formula and calculation of multiple linear regression

y_i=\beta_0+\beta_1x_i1+\beta_2x_i2+....

Yi=dependent variable

Xi=explanatory variables

\beta0=y-intercept

\betap=slope coefficients for each explanatory variable

KNN method

k-nearest neighbors algorithm is a non-paramtetric classification methods.
KNN is a type of classification where the function is only approximated locally and all computations is deferred until function evaluation.
