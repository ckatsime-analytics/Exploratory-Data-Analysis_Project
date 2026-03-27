## Exploratory Data Analysis – NYC Rental Listings

## Project Overview
This project analyzes 20,770 rental listings in New York City with 22 features. The goal is to clean, explore, and visualize the dataset to uncover pricing drivers, geographical patterns, and feature correlations.

## Data Preparation
- Dropped missing values and duplicates.
- Converted last_review to datetime.
- Adjusted data types for id and host_id.
- Removed extreme price outliers (>1500).

## Analysis Workflow
- Univariate Analysis – distributions of price, availability, reviews.
- Feature Engineering – created price_per_bed, grouped by neighbourhood.
- Bivariate Analysis – price vs room type, neighbourhood, reviews.
- Correlation Matrix – identified strong and weak predictors.
- Geographical Insights – mapped listings by borough and room type.

## Key Insights
- Room type and location are the strongest drivers of price.
- Entire homes/apartments command the highest rates.
- Manhattan and Brooklyn dominate listings and pricing.
- Reviews and availability have minimal impact on pricing.
- Beds and price_per_bed provide meaningful predictive signals.

## Visualizations
- Histograms & boxplots for price distribution.
- Scatterplots for reviews vs price.
- Heatmap for correlation matrix.
- Geographical scatterplot of listings by room type.

## Next Steps
- Extend analysis with regression models for price prediction.
- Explore time‑series trends using last_review.
- Compare borough‑level demand and supply dynamics.





