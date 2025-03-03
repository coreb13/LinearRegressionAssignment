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
- The R-squared value of the train set is 82.71% whereas the test set has a value of 81.13% which suggests that our model broadly explains the variance quite accurately on the test set and thus we can conclude that it is a good model.

- Our developed model's mean squared error is almost 0 on both the training and testing datasets which suggests that the variance is accurately predicted on the test set. The p-values and VIF were used to select the significant variables. RFE was also conducted for automated selection of variables.

- The major steps included in the python notebook are data interpretation, data visualisation, data pre-processing, model training, feature selection, residual analysis, model evaluation on the test set.

- Concepts such as EDA, p-value, VIF, RFE were used and model building was done using statsmodels library

- GrLivArea is by far the most important predictor

- The top variables are intuitive.

- Lasso is the chosen model for the final model, because it creates a simple model with the top features.

- Significant variables to predict the demand for shared bikes
  * holiday
  * temp
  * hum
  * windspeed
  * Season
  * months(January, July, September, November, December)
  * Year (2019)
  * Sunday
  * weathersit( Light Snow, Mist + Cloudy)



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
Created by [@darekarankita0] - feel free to contact me!
