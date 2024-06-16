# Airbnb Listing Analysis in Paris

## Overview
This project analyzes Airbnb listings in Paris, focusing on the impact of 2015 regulations on new hosts and average prices. Key areas include neighborhood-specific pricing, accommodation-specific pricing, and trends over time.

## Objectives

### Data Preparation
1. **Import and Clean Data**
   - Load and clean the dataset from `Listings.csv`.
   - Convert date columns (e.g., 'host_since') to datetime format.

2. **Filter Paris Listings**
   - Include only listings in Paris.
   - Select relevant columns: 'host_since', 'neighbourhood', 'city', 'accommodates', 'price'.

3. **Quality Assurance**
   - Handle missing values, particularly in 'host_since'.
   - Provide descriptive statistics for the cleaned dataset.

### Data Analysis
1. **Average Rent Price by Neighborhood**
   - Group data by 'neighbourhood' and calculate mean prices.
   - Sort neighborhoods by average price.

2. **Average Rent Price by Accommodation Capacity (Elysee)**
   - Filter data to include only listings in the most expensive neighborhood (Elysee).
   - Group by 'accommodates' and calculate mean prices.
   - Sort results by price.

3. **Trends Over Time**
   - Extract year from 'host_since' column.
   - Group data by year, calculate mean price and count of new hosts.
   - Resample data annually, aggregate mean price and count of new hosts.

### Visualization
1. **Average Rent Price by Neighborhood**
   - Horizontal bar plot showing average rent prices across different neighborhoods.

2. **Average Rent Price by Accommodation Capacity**
   - Horizontal bar plot showing average rent prices based on accommodation capacity.

3. **New Airbnb Hosts Over Time**
   - Line plot showing the number of new Airbnb hosts in Paris over the years.

4. **Average Airbnb Price Over Time**
   - Line plot displaying the average Airbnb listing price trend in Paris.

5. **Combined Plot: New Hosts and Average Price Over Time**
   - Combined plot with two y-axes showing the number of new hosts and average price over time, highlighting the impact of 2015 regulations.

## Conclusion
This analysis provides insights into the impact of 2015 regulations on the Airbnb market in Paris, revealing trends in new host dynamics and average listing prices. Visualizations confirm regulatory effects with a decline in new hosts and an increase in prices post-regulation. Further detailed analysis could explore additional factors influencing the Paris Airbnb market.
