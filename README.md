# Exploratory Data Analysis (EDA) for the King County, WA, Houses Dataset

## Summary

In this project we explore the King County Houses Dataset, with information about the house market. Our stakeholder is an investor in historic propertries in this market and is looking for high returns. We analyse how historic houses perform as investiment with respect to the market, which are the best locations for this kind of investiment and whether age and renovation are relevant for the investiment return rate. 

## Requirements

- pyenv
- python==3.11.3

### Environment

This repo contains a requirements.txt file with a list of all the packages and dependencies you will need. Before you install the virtual environment, make sure to install postgresql if you haven't done it before.

## Files

- `FetchingTheDataEDA.ipynb` Where we retrieve the data.
- `EDA_WilliamLimaProjectZacharyBrooks.ipynb` Where we perform our data cleaning and EDA
- `SlidesEDA_WilliamLima.pdf` Presentation slides
- `zachary_brooks_avatar.png` IA generated avatar for our ficticious investor
- `zipcodes_king_county_wa.pdf` A map of the zipcodes in King County

## Methodology

- We have retrieved the data using PostgreSQL.
- We have loaded this data to a *Pandas* dataframe, when we cleared the data by correcting formats and dealing with the NaN.
- We have established criterias for what is a historic property, high profit and best (i.e. most profitable) neighbourhoods.  

## Conclusions

- Historic houses outperform the market average as investiment.
- There is a seasonal effect in the house prices, making it more profitable to by in winter and sell in spring.
- Renovation and age doesn't seem to play a role in obtaining high return rates for the investiment.