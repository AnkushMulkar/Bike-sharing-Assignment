# Project Name- Bike Sharing Assignment
> 
A bike-sharing system is a service in which bikes are made available for shared use to individuals on a short term basis for a price or free. Many bike share systems allow people to borrow a bike from a "dock" which is usually computer-controlled wherein the user enters the payment information, and the system unlocks it. This bike can then be returned to another dock belonging to the same system.



## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)
* [Acknowledgements](#acknowledgements)

<!-- You can include any other section that is pertinent to your problem -->

## General Information

-A US bike-sharing provider BoomBikes has recently suffered considerable dips in their revenues due to the ongoing Corona pandemic. The company is finding it very difficult to sustain in the current market scenario. So, it has decided to come up with a mindful business plan to be able to accelerate its revenue as soon as the ongoing lockdown comes to an end, and the economy restores to a healthy state. 


In such an attempt, BoomBikes aspires to understand the demand for shared bikes among the people after this ongoing quarantine situation ends across the nation due to Covid-19. They have planned this to prepare themselves to cater to the people's needs once the situation gets better all around and stand out from other service providers and make huge profits.


They have contracted a consulting company to understand the factors on which the demand for these shared bikes depends. Specifically, they want to understand the factors affecting the demand for these shared bikes in the American market. The company wants to know:

Which variables are significant in predicting the demand for shared bikes.
How well those variables describe the bike demands

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->

## Conclusions
- Following variables are significant in predicting the demand for shared bikes - <br>
-  year  <br>
-  Workingday  <br>
-  temp  <br>
-  windspeed  <br>
-  sep  <br>
-  sat  <br>
-  Light_snowrain  <br>
-  Misty  <br>
-  summer  <br>
-  winter  

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->


## Technologies Used
import numpy as np  <br>
import pandas as pd  <br>
import matplotlib.pyplot as plt  <br>
import seaborn as sns  <br>
from sklearn.model_selection import train_test_split  <br>
from sklearn.preprocessing import MinMaxScaler  <br>
from sklearn.feature_selection import RFE  <br>
from sklearn.linear_model import LinearRegression  <br>
from statsmodels.stats.outliers_influence import variance_inflation_factor  <br>
import statsmodels.api as sm  <br>
from sklearn.metrics import r2_score  <br>
import warnings  <br>
warnings.filterwarnings('ignore')  
 


<!-- As the libraries versions keep on changing, it is recommended to mention the version of library used in this project -->

## Acknowledgements

- This project was inspired by,Upgrad


## Contact
Created by  - Ankush Mulkar

<!-- Optional -->
<!-- ## License -->
<!-- This project is open source and available under the [... License](). -->

<!-- You don't have to include all sections - just the one's relevant to your project -->