# **Airbnb Listings Data Analysis in Texas**

## **Project Overview**

This project is an exploratory data analysis (EDA) of Airbnb listings in Texas. The primary objective is to identify key factors influencing Airbnb pricing and understand variations in pricing across different cities in Texas. The analysis focuses on variables such as room type, house type, location, property characteristics, and ratings.

## **Objectives**

1. **Price Influencers:** Examine how factors like room type, house type, location, and property characteristics influence Airbnb prices.
2. **City-wise Pricing:** Investigate price variations across different cities to identify contributing factors.
3. **Top Hosts:** Identify top hosts based on ratings.
4. **Popular House Types:** Determine the most popular house types in the dataset.

## **Data Source**

The dataset used for this analysis is sourced from Kaggle, consisting of 14,861 observations and 18 variables. After data cleaning, the dataset comprises 13,246 observations and 21 variables.

## **Data Pre-processing**

- Addressed missing values and removed outliers.
- Created new variables to capture specific details like location, house type, ratings, bedrooms, and baths.
- Used summary statistics and data visualization techniques to explore patterns, outliers, and relationships.

## **Key Findings**

1. **Room Type Influence:** Different room types exhibit varying price trends, with "Entire home/apt" listings generally being the most expensive.
2. **Location Impact:** Prices vary significantly across locations, with Bee Cave having the highest prices and Austin being budget-friendly for shared room bookings.
3. **Bedrooms and Baths:** Listings with 3-5.5 bathrooms and 4-8 bedrooms tend to have higher prices.
4. **Ratings and Reviews:** No strong linear correlation between ratings, number of reviews, and prices, though some patterns are noticeable.
5. **Neighborhood Effect:** Neighborhoods significantly influence listing prices, with 78712 having the highest mean price and 78719 the lowest.
6. **Popular House Types:** "Home" is the most popular house type, followed by "Rental Units" and "Condos."
7. **Top Hosts:** The top 10 hosts are based in Austin and have perfect ratings.

## **Conclusion**

Room type, house type, location, neighborhood, number of bedrooms, and bathrooms are significant determinants of Airbnb prices in Texas. Ratings and reviews have some influence on pricing, but the correlation is not strong. Future research could expand the dataset to include more cities and longer time frames.

## **Repository Structure**

- `data/`: Contains the dataset used for analysis.
- `scripts/`: Includes R scripts for data cleaning, EDA, and visualization.
- `output/`: Contains the results of the analysis, including visualizations and summary statistics.

## **References**

1. [R for Data Science by Hadley Wickham and Garrett Grolemund](https://r4ds.had.co.nz)
2. [Dataset from Kaggle](https://www.kaggle.com/datasets/deeplearner09/airbnb-listing)

## **Authors**

- Niharika Patil
- Pratiksha Gadhe
- Yashi Agarwal

## **GitHub Repository**

[Airbnb Listings Data Analysis](https://github.com/pratikshagadhe23/Airbnb_EDA)
