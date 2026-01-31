# Airbnb Market Analysis: Columbus vs New York

## Author
Elaine Schaft

## Project Overview
This project analyzes Airbnb listing data to compare the Columbus, Ohio and New York City markets. The goal is to help hosts and travelers understand prices, bookings, and reviews, so they can find the best neighborhoods, improve listings, and make smarter decisions about when and where to book.

## Research Questions

1. Which Columbus neighborhoods have the most affordable listings for weekend stays?
2. Do listings with more reviews get booked more often?
3. Do entire homes get higher review scores than private or shared rooms? 
4. Are weekend bookings more expensive than weekday bookings in Columbus and NYC?
5. Do hosts with multiple listings get higher review scores than hosts with only one listing?

## Data Source Mapping

| # | Question | Data Needed | Source | Data Type |
|:-:|:---------|:------------|:-------|:----------|
| 1 | Which Columbus neighborhoods have the most affordable listings for weekend stays? | price, neighborhood, room type, availability | listings.csv, calendar.csv  | structured |
| 2 | Do listings with more reviews get booked more often? | number of reviews, availability | listings.csv, calendar.csv | structured |
| 3 | Do entire homes get higher review scores than private or shared rooms? | room type, reviews per month, number of reviews | listings.csv | structured |
| 4 | Are weekend bookings more expensive than weekday bookings in Columbus and NYC? | date, price, availability | calendar.csv | structured |
| 5 | Do hosts with multiple listings get higher review scores than hosts with only one listing? | host listings, review scores rating | listings.csv, reviews.csv | structured |

## Data Overview
- **Columbus, Ohio:** 2877 listings (as of Sept 26, 2025)
- **New York City:** 36261 listings (as of Dec 4, 2025)
- **Primary data source:** [Inside Airbnb](http://insideairbnb.com/get-the-data)

## Project Status
- [x] Initial data exploration
- [x] Research questions defined
- [x] Data sources mapped
- [ ] Data downloaded and cleaned
- [ ] Analysis complete
- [ ] Visualizations created