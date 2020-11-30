---
layout: page
title: jugaad-internship
permalink: /jugaad/
---

#Internship at Jugaad Analytics


I created an end to end system for analysing the dataset for Hinekein beers. This was implemented using OSEMN(obtain, scrub, explore, model, interpret) structure. The dataset was extremely dirty, so first task was to develop a generic class to clean the dataset. The constructor for this class takes a table as an input, and takes appropriate decisions and removes the unnecessary information including redundant columns, checks for missing values, and then aggregating the data by dates.

Next element was to do visualization and descriptive statistics from the datasets to gain insight from the data. For that I used python matplotlib and seaborn in case of visualization and for stats, used statsmodel and scikit-learn library.
This gave me an idea of the basic statistic entities along with hiw the tablular valies are coorelated with each other and what type of ML model can be deployed for the situation.
Now there were columns which showed the quantity of beers sold for different time period. Next task was to create a forecasting model to predict the approximate sales in the coming time on daily, monthly and yearly basis. For that I integrated two models initially namely ARIMA and SARIMA models which stands for autoregressive integrated moving average models. In case of time series, the basic assumption of independence of data is voilated. So for that we have to use slightly different models than the convention ML models.
So training the model using Arima and sarima with different parameters and comparing the results I forecasted the values for the next dates on monthly and weekly basis.
s
