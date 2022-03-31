# Default-of-Credit-Card-Clients
# Analysis of Default of Credit Card Clients Against Their Background

Analysis of credit card cardholders' background using Machine Learning on both quantitative and qualitative responses. This dataset contains information on default payments, demographic factors, credit data, history of payment, and bill statements of credit card clients in Taiwan from April 2005 to September 2005.

## Abstract
To find out the best fit algorithm for amount of given credit in NT dollars against other factors, which are more important variables using Bayesian information criterion.

## Exploratory Data Analysis
To generate insights of "Default of Credit Card Clients Dataset", the first step is Exploratory Data Analysis. I performed initial investigations on the data and summarized statistics and graphical representations using `ggplot2` in R.

## Quantitative factors as responses
Machine learning on amount of given credit in NT dollars against other factors.

There are 24 factors against amount of given credit. In order to aviod overfitting, I selected the most important factors using forward stepwise selection and chose Bayesian Information Criterion (BIC) for determining the cross-validated prediction error. The Bayesian Information Criterion (BIC) gives unnecessary variable much greater penalty, so it can more efficient to aviod overfitting. 

