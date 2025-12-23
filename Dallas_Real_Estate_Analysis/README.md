# Dallas Real Estate Price Analysis

## Project Overview
This project analyzes residential real estate listings in Dallas, Texas to understand which factors most strongly influence home sale prices. The analysis focuses on data preparation, variable selection, and exploratory analysis to support predictive modeling.

## Business Problem
Accurately predicting home prices is essential for real estate professionals and buyers. Sale price is influenced by property characteristics, location, and market conditions. The goal of this project is to identify the most relevant variables that contribute to home pricing and prepare the data for modeling.

## Data Description
The dataset contains residential real estate listings for the Dallas area, including variables such as:
- Property type
- ZIP code and location
- Number of bedrooms and bathrooms
- Square footage
- Year built
- Days on market
- Listing price

## Data Cleaning & Preparation
The following steps were performed:
- Removed variables with no predictive value or redundant information (e.g., listing metadata, URLs)
- Reclassified categorical and continuous variables
- Evaluated missing values and outliers
- Excluded variables with excessive missing data (e.g., HOA fees, lot size)
- Applied automated data imputation where appropriate

## Key Variables Used
Final variables retained for analysis included:
- Price
- ZIP code
- Location
- Bedrooms
- Bathrooms
- Square footage
- Property type

## Exploratory Analysis
Exploratory analysis included:
- Distribution analysis of key numeric variables
- Identification of skewness and outliers
- Geographic visualization by ZIP code
- Comparison of property characteristics and price

## Tools Used
- JMP
- Exploratory Data Analysis techniques
- Data imputation and variable selection methods

## Key Takeaways
- Square footage, location, and bedroom/bathroom count are strong indicators of price
- Several listing attributes provide little predictive value and were removed
- Data cleaning and variable selection significantly improved data quality for modeling

## Project Type
Academic project completed as part of a Predictive Analytics course.

