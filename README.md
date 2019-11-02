# Datathon Noviembre 2019 [Dani-Jordi-Peter]

## Overview
We are hired by a Cookie Making Company (Flea Cookies) to predict the quality of the cookies they make before they hit the markets.

## Ideas and hypothesis
	* Does calorie content have correlation with quality?
	* Does calorie content have correlation with quality?
	* Has the baking temperature something to do with perceived quality?

## Data preparation
### EDA
We are provided a dataset containing features of the cookies as well as their overall quality.
	* Shape: (5918, 16)
	* Target variable:
	* Numerical variables: sugar to flour ratio, sugar index, bake temp, chill time, calories, density, pH, grams of baking soda, bake time, quality, weight, diameter, crunch factor, aesthetic appeal.
	* Categorical variables: Butter type (nominal, binary). Mixins (nominal).

### Data Wrangling and cleaning
	* Chaning
	* Checking dtypes, dropping NaN values and checking that the content of the columns is correct.
	* Dealing with outliers and illogical values (negative values, pH out of range, extremely high temperatures).
	* Imputation of extreme values to the mean.

### Feature Engineering
	* Creating a column for each ingredient of Mixins and transforming each column to a binary one (0 - False and 1 - True).
	* Scaling of the numerical variables as their magnitude varies highly (pH versus temperature, etc.)
	* Using Dummies for Butter Type

### Algorithm selection, Model Creation and Modification


### Conclusions:
