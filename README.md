
# US Airline Flight Routes and Fare Data Analysis







## Project Overview
This project analyzes a 30 year dataset of US airlines routes and fares focusing on identifying trends in flight fares, routes, passengers, and key routes. The analysis aims to help airlines, airports, and policymakers understand the industry's evolution and make data-driven decisions.

## Dataset
The dataset includes domestic flight data from 1993 to 2024 (excluding 1995) and contains over 120,000 rows and provides a detailed view of air traffic and pricing dynamics across the U.S. over three decades.

## Data Sources
The dataset used for this project is titled "US Airline Flight Routes and Fares 1993-2024", which was downloaded from Kaggle in CSV format.

## Tools & Libraries Used :
- __Jupyter Notebook__ : For interactive coding and data visualization.
- __Pandas__ : For data manipulation and analysis.
- __Matplotlib__ : For creating static, and interactive visualizations.
- __Seaborn__ : For enhanced statistical data visualization.
- __Plotly__ : For interactive and dynamic visualizations.
- __Geopy__ : For geocoding and geographical calculations.


## Data Cleaning / Preparation
During the initial data preparation phase, the following tasks were performed:
- Loaded and inspected the data.
- Removed unnecessary columns like tbl, citymarketid, airportid, etc.
- Deleted all the rows having null values.
- Checked data for inconsistency and remove outliers in passenger column.

## Exploratory Data analysis
1. __Correlation Map__
- Generated a correlation heatmap to understand the relationships between key numerical variables, such as fare prices, passenger numbers, and distances.
2. __Average Fare Over the Years__
- To track changes in ticket prices over time, plotted a line chart showing the trend of average fares from 1993 to 2024.
3. __Relationship Between Fare and Passengers__
- Created a scatter plot to examine the relationship between fare prices and passenger numbers.
4. __Quarterly Passenger Trends Over Time__
- Analyzed passengers trend on a quarterly basis to observe seasonal fluctuations in air travel.
5. __Comparison of Market Share Over the Years__
- Compared the market shares of large carriers and low fare carriers over time using an area chart. 
6. __Fare Percentage Difference Across States__
- Created a heatmap to visualize fare percentage differences between large carriers and low fare carriers across states to identify regional pricing trends.
7. __Top Routes by Average Fare__
- Identified the top 20 routes with the highest average fares and displayed them using a bar chart.
8. __Fare Patterns of Top Carriers__
- Created a line chart to analyze the fare patterns of the top carriers over time.
9. __Busiest Airports by Passengers__
- To showcase airport traffic, used a horizontal bar chart displaying the busiest U.S. airports based on passenger numbers.
10. __Geomap of Number of Routes by Cities__
- A geographical map was created to visualize the number of routes originating from or arriving at each city.

## Key Insights

The analysis of the U.S. airline data revealed several important trends and patterns:

- There was a moderate negative correlation between fare prices and passenger numbers,  indicating that lower fares generally attract more passengers.

- The January-March quarter consistently records the lowest number of passengers, while the April-June quarter typically sees the highest number of passengers.

- Routes involving major cities like New York, San Francisco, and Miami tend to have higher average fares and rank among the top routes by fare.

- Key cities like Dallas, Chicago, and Boston remain central hubs with the highest number of routes, contributing to their dominance in the airline industry.

## References
- Documentation: Pandas, Seaborn, GeoPandas
- Stack Overflow

## Limitations

Rows were removed from the dataset where both large carriers and low-fare carriers have the same market share, as this situation is not feasible in the analysis.

## Conclusion

This project provided insights into the U.S. airline industry, revealing long term trends in passenger traffic, fare prices, and airline competition. By leveraging various analytical techniques, I was able to uncover key patterns that can inform decision making for airlines, airports, and policymakers.