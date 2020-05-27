# Seattle-Airbnb-Analysis

# Outline

# Installation

In this project, I used Juypter Notebook and the package below to do data analysis.
 
- pandas = 0.25.1
- matplotlib = 2.2.4
- folium = 0.5.0

# File Description

There are total 7 files in this project. I divided them into three parts: Datasets, Analysis Notebook and related files, and Result file as shown below.

## Datasets

- **calendar.csv**: including listing id and its availability and price for a specific day.
- **listings.csv**: including full descriptions and information of listing id.
- **reviews.csv**: including unique reviewer id and their comments.
Source of this datasets: [Kaggle-Seattle Airbnb Open Data](https://www.kaggle.com/airbnb/seattle/data)



## Analysis Notebook and related files

- **Seattle Airbnb Analysis.ipynb**: Juypter Notebook including my main analysis work to answer the research questions.

- **neighborhoods.geojson**: geojson file of Seattle neighborhoods boundary for drawing choropleth map.
Source of this file: https://github.com/seattleio/seattle-boundaries-data/blob/master/data/neighborhoods.geojson

## Result file

- **Mean price in Seattle.html**: choropleth map in Seattle which display the mean price per night per bed in each neighboorhoods.
- **Reference table for price setting.csv**: Reference table for Seattle Airbnb hosts to set listings prices. This table includes statistical columns of price based on different neighborhoods.


# Project Objective

The purpose of this project is to provide the suggestions for Airbnb newbie to start their business.  

To do so, I set up following research questions for further analysis:

1. Does the location influence price setting?
  (1) Do different neighborhoods in Seattle have different prices?
  (2) Can we have a reference table that helps Airbnb hosts to decide their price based on neighborhoods

2. Does the price change periodically?
  (1) Does the price change monthly?
  (2) Does the price change between weekdays and weekends ?
  (3) Is the price higher on holidays than other days?

3. What are the main attributes that super hosts are different from general hosts?

# Results

- Both location and time period influence prices of listings.
- Different neighborhoods in Seattle have different listing price. 
  Please see the choropleth map: Mean price in Seattle.html
- I created a reference table for Airbnb hosts to set price based on their listing location. 
  Please see the reference table: Reference table for price setting.csv
- It is suggest to raise listing price from June to August and lower listing price from January to March.
- Saturday and Friday is the two high demand days in a whole weeks. It is suggest to raise listing price during these two days.
- Holidays have no specific influence on the price. As a result, there's no need to adjust price during holidays.
- Cleanliness is the most important items that distinguish super hosts and general hosts. Followed by Value and Accuracy. we suggest Airbnb hosts to focus more on these items.


Please visit my Medium article to see whole story and actionable conclusions.

# Licensing and Acknowledgements

Thanks to the open source listed below: 

- [Kaggle-Seattle Airbnb Open Data](https://www.kaggle.com/airbnb/seattle/data)
- [Seattle neighborhoods boundary](https://github.com/seattleio/seattle-boundaries-data/blob/master/data/neighborhoods.geojson)


