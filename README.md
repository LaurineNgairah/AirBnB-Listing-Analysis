# AirBnB Listing Python Analysis: Impact of Regulations on the Paris Market

## Project Overview
This project involves a comprehensive analysis of AirBnB listings in Paris to evaluate the effects of recent regulations on the market, specifically focusing on pricing. With AirBnB's growing popularity in Paris, regulatory measures were introduced to limit the number of properties listed in the city. This analysis seeks to understand how these regulations, which began in 2015, have influenced listing prices and market dynamics.

## Problem Statement
In 2015, Paris implemented regulations to limit the number of AirBnB listings. The primary objective of this project is to assess how these regulations have impacted listing prices. We aim to determine whether the regulatory changes have significantly affected pricing and to identify the factors influencing pricing in the Paris AirBnB market.

## Objectives
1. Data Exploration and Profiling
- Examine the AirBnB listing data for Paris to identify any data quality issues, such as missing values, outliers, or inconsistencies.
- Ensure the dataset is clean and accurate for further analysis.
2. Data Preparation and Reformatting
- Reformat and transform the dataset to facilitate effective visualization and analysis, making sure all variables are correctly formatted (e.g., date, price).
- Create new features or calculated fields if needed to enhance the analysis.
3. Data Visualization and Insight Generation
- Develop visual summaries to highlight key factors influencing AirBnB listing prices in Paris.
- Use visual tools such as charts, graphs, and heatmaps to present the data clearly and concisely.
- Analyze trends and patterns to provide insights into how the 2015 regulations have impacted pricing and the overall Paris AirBnB market.

## Key Deliverables
- A clean and well-structured dataset ready for analysis.
- Visualizations illustrating the relationships between pricing and factors such as location, property type, and size.
- Insights and recommendations based on the analysis, focusing on the impact of the 2015 regulations on the Paris AirBnB market.

## Tasks and Methodology
### Task 1: Data Profiling and Quality Assurance
1. Import and Open Data
- Load the listing CSV file with appropriate encoding to handle special characters.
- Ensure the entire dataset is read into memory to avoid issues with data type inference.
2. Filter Data
- Select relevant columns (host_since, neighborhood, city, accommodates, price).
- Filter the dataset to include only entries where the city is Paris.
3. Check for Missing Values and Statistics
- Identify and address missing values.
- Calculate minimum, maximum, and average values for numeric fields like accommodates and price.

### Task 2: Data Preparation for Visualization
1. Group by Neighborhood
- Create a table to group Paris listings by neighborhood and calculate the mean price, sorted from low to high.
2. Group by Accommodations in the Most Expensive Neighborhood
- Filter the dataset to focus on the most expensive neighborhood.
- Group by accommodates to calculate the mean price for each accommodation size.
3. Group by Host Since Year
- Create a table to group listings by the year extracted from host_since.
- Calculate the average price and count the number of new hosts for each year.

### Task 3: Data Visualization and Summary
1. Average Price by Neighborhood
- Create a horizontal bar chart to show the average price by neighborhood in Paris.
**Insight:** The Elysee neighborhood has the highest average price, while Menilmontant has the lowest.
2. Average Price by Accommodations
- Create a horizontal bar chart of the average price by accommodates in the most expensive neighborhood.
**Insight:** Listings that accommodate more guests tend to have higher prices.
3. Line Charts of New Hosts and Average Price Over Time
- Create two line charts: one for the count of new hosts over time and one for the average price.
**Insight:** There was a sharp decrease in new hosts after 2015 due to regulations. The average price showed significant fluctuations, with a notable decrease in 2021, indicating possible market corrections or other influencing factors.

### Overall Findings:
- **Impact of Regulations:** The introduction of regulations in 2015 led to a significant decrease in new host registrations and initial increases in average prices, followed by notable fluctuations and a sharp decline in 2021.
- **Factors Affecting Pricing:** Key factors influencing pricing include the number of guests a property can accommodate and the neighborhood location, with Elysee being the most expensive and Menilmontant the least expensive neighborhood.

## Conclusion
This analysis provides valuable insights into how regulatory changes have impacted the AirBnB market in Paris and can help guide future decisions regarding listings and potential regulatory responses.
