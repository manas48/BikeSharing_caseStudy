# Multiple Linear Regression (Bike Sharing Assignment)

## Introduction
In this assignment we need to build a multiple linear regression model for the prediction of demand for shared bikes.

## Problem Statement
	A bike-sharing system is a service in which bikes are made available for shared use to individuals on a short term basis for a price or free.
	Business wants to understand the factors on which the demand for these shared bikes depends.Specifically, they want to understand the factors 
	affecting the demand for these shared bikes in the American market. The company wants to know:
				Which variables are significant in predicting the demand for shared bikes.
				How well those variables describe the bike demands

## Business Goal:
It is required to model the demand for shared bikes with the available independent variables. 
It will be used by the management to understand how exactly the demands vary with different features. 
They can accordingly manipulate the business strategy to meet the demand levels and meet the customer's expectations. 
Further, the model will be a good way for management to understand the demand dynamics of a new market.
<br>

## Problem Solving Methodology
1. Data Understanding-
	- Understanding and working with data dictionary and getting good knowledge of all the columns and their domain specific uses.
2. Data Visualization-
	- Perform EDA to understand various variables.
	- Check the correlation between the variables.
3. Data Preparation-
	Create dummy variables for all the categorical features.
	Divide the data to train & Test.
	Perform Scaling.
	Divide data into dependent & Independent variables.
4. Data Modelling & Evaluation-
	Create Linear Regression model using mixed approach (RFE & VIF/p-value).
	Check the various assumptions.
	Check the Adjusted R-Square for both train & Test data.
	Report the final model.

<br>
## Conclusion:

	 - From R-Sqaured and adj R-Sqaured value for both Traina nd test don't have much variance and can explain overall around 80% of bike demand.
	 - The Coeffiencients of the variables explain the factors affecting the bike demand.

## Technologies Used
- Python - version 3.x

## Libraries Used
- Pandas , Numpy , Matplotlib , Seaborn , sklearn , statsmodels

## Contact
Created by [@manas48] - feel free to contact me!
