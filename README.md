# Udacity Project1
# Seattle Airbnb Exploratory Analysis
This is a project aimed at analysing the datasets provided by Airbnb on its activity in Seattle, WA, USA. The project employs the use of the CRISP-DM process and explores three separate datasets.

These datasets describe the listing activity of homestays in Seattle since 2008.

## Content
The following three Airbnb datasets are included:

Listings, including full descriptions and average review score

Reviews, including unique id for each reviewer and detailed comments

Calendar, including listing id and the price and availability for that day

## Data
The data can be found on Kaggle [here](https://www.kaggle.com/airbnb/seattle).

## Installations:
This project requires Python 3.x and the following Python libraries installed:
Numpy
Pandas
Matplotlib
Datetime
Scikit-Learn

## Questions explored.
1. Which months have the most Airbnb listings?
2. Which months fetch the highest prices?
3. What is the total revenue that can be generated each month?
4. Which neighbourhoods are the most expensive and the cheapest?
5. How much time do the hosts take in responding?
6. Which are the top ten neighbourhoods in terms of number of listings?
7. What are the main types of properties available?
8. Which factors affect ratings and prices the most?


## Results:
The results and analyses are included in the jupyter notebook. A detailed explanation of the results is posted on Medium.

Some conclusions are as follows :
1. December has the most number of lisitngs, followed by October and November. It can be concluded that October-December are the peak months.
2. December fetches the highest average price, followed by June.
3. December is the peak revenue generating month, followed by August.
4. The maximum average price is $231.705882 and it is concluded that Southeast Magnolia has the most expensive listings. Rainier Beach is the cheapest neighbourhood with an average price of $68.555556.
5. Most hosts (40% above) reply within an hour.
6. Broadway has the most number of listings.
7. Most of the listed properties are either houses or apartments.
8. Bedrooms offered by the host seem to be the most influential factors affecting the price, follwed by beds and bathrooms. Minimum and maximum nights offered do not affect the price as such.

## Linear Regression
We have also attempted to predict prices using Linear Regression.
The R2 score came out to be 40%.
