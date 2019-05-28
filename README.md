# Data Engineering Project

## What problem will we solve? ##
We will look at the most populous U.S. cities and identify which ones are the most expensive and the most affordable to live in. This will help us decide which city we'd like to move to next.

## What datasets will we use? ##

We will scrape three datasets: <br/>

1) Wikipedia [List of United States cities by population](https://en.wikipedia.org/wiki/List_of_United_States_cities_by_population) data, which lists the most populous U.S. cities

2) [Zillow Home Value Index](https://www.zillow.com/research/zhvi-methodology-6032/) data, an estimate of median home values by city. 

3) Wikipedia [Household income in the United States](https://en.wikipedia.org/wiki/Household_income_in_the_United_States) data, which lists 2017 median household income by state 

## How will we use these datasets to solve the problem? ##
We will append (2) median home value data and (3) household income data to the (1) list of most populous U.S. cities, and then calculate a "Cost Score", which shows for each city how many years of income is required to purchase a median value home. This tells us, relative to other cities, how costly it is to live in a particular city. We will then create a "Cost Rank" based on this score. </br>

## What steps will we take to do this? ##

We will: <br/>

I. Scrape the Data <br/>

II. Join the Data <br/>

III. Analyze the Data

## For step by step code, refer to 'DataEngineering.ipynb'. The output of this notebook code is 'topCitiesJoined.csv', whcih lists the most populous U.S. cities as well as their 'Cost Score' and 'Cost Rank'. This CSV is ready to be uploaded to a BigQuery table.
