<img src="Seattle.jpg" style ="width: 5000px;"/>

## Introduction

In the rapidly evolving landscape of the sharing economy, Airbnb has emerged as a prominent platform for short-term rental accommodations worldwide. With its diverse range of listings, from cozy apartments to luxurious villas, Airbnb provides an invaluable data set that reflects various aspects of the hospitality industry. Analyzing Airbnb data offers insights into key trends such as pricing strategies, occupancy rates, guest preferences, and geographic demand. This analysis aims to leverage Airbnb’s extensive data to uncover patterns and actionable insights that can benefit hosts, travelers, and policymakers. Through a comprehensive examination of variables like property types, booking behaviors, and reviews, we aim to understand the drivers behind successful listings, regional pricing fluctuations, and customer satisfaction metrics. By exploring these dimensions, we can better understand the factors that contribute to market success and areas where hosts or the platform may need improvement.

This study will dive into the Airbnb dataset to extract meaningful insights, highlight significant trends, and suggest data-driven strategies for optimizing both host offerings and guest experiences.

## Table of Contents

1. The Libraries That I Have Used
2. My Project Motivation
3. File Descriptions
4. Summary Of The Results
5. Acknowledgements

## The Libraries That I Have Used

The project was implemented using Anaconda distribution of Python 3.0. Moreover I have used the following python libraries:

1. Matplotlib
2. NumPy
3. Pandas
4. Datetime
5. Calender

## My Project Motivation

I was interested in exploring the AirBnB dataset for Seattle. I wanted to better understand the pricing trends, review sentiments and pricing prediction. Some of the questions that I have analyzed are:

1. How does the pricing increase or decrease by season?
2. What is the peak season in Seattle?
3.How does the pricing increase or decrease by neighborhood?
4. Which ones are the priciest neighborhoods in Seattle?
5. How does property types within neighborhoods impact price for the most expensive neighborhoods and most common property types?
6. Can we predict a price for a given listing?
7. What factors of the listing correlate best for predicting the price?

## File Descriptions

The Jupyter notebook showcases the analysis done in order to explore the dataset, the data prepartion and wrangling as well as the building of prediction models in order to answer the questions above. The notebook contains markdown cells to help with documentation of the steps as well as to communicate findings based on each analysis.

For reference an HTML version of the notebook is also available.

Lastly, the Data folder contains the dataset from Kaggle (https://www.kaggle.com/airbnb/seattle). It contains 3 files:

calendar.csv: calendar availability of listings and price
listings.csv: information about all the available listings
reviews.csv: listing reviews by the users

## Summary Of The Results

The following key findings from the analysis are summarized below:

1. It was found that the peak season in Seattle is during the summer months from June to August, with the absolute peak being in July.

2. The "Fairmount Park" neighborhood was the priciest neighborhood in Seattle, followed by Industrial District. Roxhill was the cheapest.

3. Looking further at neighborhoods and property types, I found out that Tents are the most booked by property type following by dorm and tenthouse.

4. 3308979 id charges the most. Average charged price of top 10 ids is 900.

5. Most of the people contact within an hour which shows how much id the popularity of AirBnB

6. The most popular Neighbourhood in Seattle is Broadway which is far higher than the following Belltown.

7. There is many fluctuations in the price by the cleansed neighbourhood but we can see that area between Pioneer Square and Wedgewood is most expensive following by Pioneer Square. But we can also see some areas around Pioneer Square is least expensive

8. Most of the booking were made for Entire Home/Apt. following by Private room and least for Shared Room

## Acknowledgements

Credit to the AirBnB dataset published by AirBnB and Kaggle for hosting it, the dataset here: https://www.kaggle.com/airbnb/seattle

## Blogpost

The link for the Blog is https://medium.com/@rohit5206/seattle-property-data-analysis-df3277a95ef9
