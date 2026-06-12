# Market Trend Analysis

Project Link - https://docs.google.com/spreadsheets/d/1Rc5bNWOOoLLAwGpC2InYQUGtS0NY5pJjr34JHG0Q1kE/edit?usp=sharing

## About Dataset: 
Welcome to New York City, one of the most-visited cities in the world. There are around 25K Airbnb listings in New York City to meet the high demand for temporary lodging for travelers, which can be anywhere between a few nights to many months.

**The goal is to explore the factors that influence listing prices.**

In this project, we will take a closer look at the New York Airbnb market by combining data from multiple file types like `.csv`, `.tsv`, and `.xlsx`. The analysis is performed using google sheets.  

This dataset consists of 25k listings across Brooklyn, Bronx, Queens, Staten Lands and Manhattan. Around 7k hosts have resided in these cities with prices ranging from $10 - $7500. The time period this dataset consists from Jan 2019 till July 2019. 

## Problem Statement:
Using this dataset we will look at the trends of people lodging in these temporary resident
Understand pricing strategy, look at the monthly trend across these cities and also look out for top neighbourhoods which will help us understand consumer behaviour. 

## Column Description - 
Hostname - point of contact It tells the customer who they will be communicating with to book the stay, ask questions, or check in.

### data/airbnb_price.csv
This is a CSV file containing data on Airbnb listing prices and locations.
listing_id: unique identifier of listing
price: nightly listing price in USD
nbhood_full: name of borough and neighborhood where listing is located

### data/airbnb_room_type.xlsx
This is an Excel file containing data on Airbnb listing descriptions and room types.
listing_id: unique identifier of listing
description: listing description
room_type: Airbnb has three types of rooms: shared rooms, private rooms, and entire homes/apartments

### data/airbnb_last_review.tsv
This is a TSV file containing data on Airbnb host names and review dates.
listing_id: unique identifier of listing
host_name: name of listing host
last_review: date when the listing was last reviewed

## Report
Based on the average pricing of Borough, Manhattan is expensive, having a price of $184 .
Brooklyn $121.97 and Queens $92.81 while lowest pricing is in Staten land $86.04 and Bronx $79.24

By looking at the room type average pricing,
An entire home / apartment that costs around $197. The private room cost $81.67 and shared room costs $53.65 

Manhattan consists of 10322 listings making it highest in New York city. Brooklyn consists of 10460 listings, second highest. While other borough listings count Queens 3456 , Staten Island 267 having the lowest listing count and Bronx with 697 listings.

As per above stats this tells us that Manhattan and Brooklyn have high pricing and more number listings. 

As per monthly stats, listings were last reviewed in June 2019 ( 12596 listings ) highest of 2019, In July it had a sudden drop of 18.75% with only 4725 listings. The all time lowest listing was done in February having only 470 listing count. 

By looking at the listings distribution price strategy most listings were affordable ( 36.4% ), ( 13.0%) were in budget, ( 21.1% ) were in mid-range. Only 1.6% were ultra luxury, 19.7% were premium and 8.1% were luxury.

**This report concludes that factors like pricing, the Borough type and room type influences the marketing trends in New York cities.**

