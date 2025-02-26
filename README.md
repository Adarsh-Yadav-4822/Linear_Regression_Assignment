# Bike Sharing
> A bike-sharing system is a service in which bikes are made available for shared use to individuals on a short term basis for a price or free. Many bike share systems allow people to borrow a bike from a "dock" which is usually computer-controlled wherein the user enters the payment information, and the system unlocks it. This bike can then be returned to another dock belonging to the same system.
> A US bike-sharing provider BoomBikes has recently suffered considerable dips in their revenues due to the ongoing Corona pandemic. The company is finding it very difficult to sustain in the current market scenario. So, it has decided to come up with a mindful business plan to be able to accelerate its revenue as soon as the ongoing lockdown comes to an end, and the economy restores to a healthy state.


## Table of Contents
* Multiple Linear Regression Model
* Technologies Used
* Conclusions
* Acknowledgements


## Multiple Linear Regression Model

# Approach:
- Reading and Understanding the Data
- Exploratory Data Analysis
- Preparing the Data for Model
- Training the model
- Residual Analysis
- Predictions and evaluating model on the test sett


## Technologies Used
- Python library - Pandas 2.2.2
- Python library - Numpy 1.26.4
- Python library - Seaborn 0.13.2
- Python library - Matplotlib
- Python library - Statsmodel 0.14.2
- Python library - sklearn 1.4.2
- Jupyter Notebook 7.0.8


## Conclusions
- We can use below equation to predict the cnt and use the same to increase the cnt and eventually the revenue:
- cnt=0.3112 + 0.2370*yr + 0.0492*workingday + 0.4088*atemp - 0.154*hum - 0.106*windspeed - 0.0738*mnth_Dec - 0.0907*mnth_Nov + 0.0651*mnth_Sep - 0.159*season_sprig + 0.0901*season_winter + 0.0538*weekday_Sat - 0.2275*weathersit_Light_Snow - 0.0557*weathersit_Mist
- On a relatively hotter day the bike usage is likely to increase, as the cnt will increase by 0.4088 with 1 unint increase in atemp
- During winters and on saturdays the bike usage is supposed to increase.
- Bikes are being preferred during the workingday as compared to the holidays meaning bikes are being used for commute to and from offices
- windspeed, hum, season_sprig, weathersit_Light_Snow, weathersit_Mist impacting the bike usage neagtively


## Acknowledgements
This project has been completed by Adarsh Yadav, adarshy4822@gmail.com


## Contact
Created by [@Adarsh-Yadav-4822] - feel free to contact me!
