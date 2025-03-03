# Project Name
> Outline a brief description of your project. BoomBikes, a US-based bike-sharing provider, has recently experienced a significant decline in revenue due to the ongoing COVID-19 pandemic. Struggling to sustain itself in the current market conditions, the company has decided to develop a strategic business plan to boost revenue once the lockdown ends and the economy stabilizes.

In such an attempt, BoomBikes aspires to understand the demand for shared bikes among the people after this ongoing quarantine situation ends across the nation due to Covid-19. They have planned this to prepare themselves to cater to the people's needs once the situation gets better all around and stand out from other service providers and make huge profits. The company wants to know:

Which variables are significant in predicting the demand for shared bikes. How well those variables describe the bike demands

## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)
* [Acknowledgements](#acknowledgements)


## General Information
* Build a linear regression model to find the variables which have a significant impact on the demand for shared bikes.
* What is the background of your project?
* What is the business probem that your project is trying to solve?: variables that affect the demand for shared bikes and the extent of their impacy
* What is the dataset that is being used?


## Conclusions
- The R-squared value for the training set is 82.71%, while the test set shows a slightly lower value of 81.13%. This indicates that our model effectively captures the variance in the test set, suggesting it is a reliable and robust model.

- The mean squared error of our developed model is nearly zero for both the training and testing datasets, implying that the model predicts the variance with high accuracy on the test set. We utilized p-values and Variance Inflation Factor (VIF) to identify significant variables, and Recursive Feature Elimination (RFE) was employed for automated variable selection.

- The key steps outlined in the Python notebook include data interpretation, data visualization, data preprocessing, model training, feature selection, residual analysis, and model evaluation on the test set.

- Techniques such as Exploratory Data Analysis (EDA), p-values, VIF, and RFE were applied, with the model constructed using the statsmodels library.

- GrLivArea stands out as the most critical predictor.

- The top variables align with intuitive expectations.

- Lasso was selected as the final model due to its ability to produce a straightforward model incorporating the most important features.

- Key variables significantly influencing the demand for shared bikes include:
  * Holiday
  * Temperature (temp)
  * Humidity (hum)
  * Windspeed
  * Season
  * Months (January, July, September, November, December)
  * Year (2019)
  * Sunday
  * Weather conditions (Light Snow, Mist + Cloudy)


## Technologies Used
- Python - version 3.11.4
- Matplotlib - version 3.7.1
- Numpy - version 1.24.3
- Pandas - version 1.5.3
- Seaborn - version 0.12.2
- Statsmodels - version 0.14.1
- Scikit-learn - version 1.4.2


## Acknowledgements
- This project was inspired by Upgrad


## Contact
Created by [@coreb13] - feel free to contact me!
