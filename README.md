# Predicting overdose mortality

## Goal
The overall goal of this project was to build a linear regression model that would predict the overdose mortality rate per county in 2016.

## Data Sources
Target variable:
* Crude mortality rate per county in 2016 --> scraped from CDC WONDER database using Selenium and BeautifulSoup

Predictor variables:
* Demographic characteristics: median age, % Caucasian, % high school graduates or above
* Economic characteristics: median household income, % poverty rate, % unemployment
* Geographic: census region division
* Medical: PMP (prescription monitoring program) age in years in 2016, opioid prescribing rate per 100 people per county in 2016

Demographic and economic data was obtained using the US Census API. US regional divisions also obtained from US Census maps. PMP age was scraped from PDMPassist.org, and opioid prescribing rate per 100 people per county was scraped from CDC tables.
