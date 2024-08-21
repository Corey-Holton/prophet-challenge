# prophet-challenge
## Module 8 Challenge
# Forecasting Net Prophet
# Overview
This project aims to analyze the financial and user data of MercadoLibre, the most popular e-commerce site in Latin America, to uncover patterns in Google search traffic and its relation to stock price. The project is divided into four main steps:

- Finding Unusual Patterns in Hourly Google Search Traffic
- Mining the Search Traffic Data for Seasonality
- Relating the Search Traffic to Stock Price Patterns
- Creating a Time Series Model with Prophet
# Project Structure
- Step 1: Find Unusual Patterns in Hourly Google Search Traffic

In this step, we analyze Google search traffic data for MercadoLibre during May 2020, the month in which the company released its quarterly financial results. We visualize the data and calculate the total search traffic to identify any unusual patterns and compare it to the monthly median across all months.

- Step 2: Mine the Search Traffic Data for Seasonality

This step involves mining the Google search traffic data for seasonal patterns. We analyze the data by grouping it by the hour of the day, day of the week, and week of the year to identify peak traffic times and days, and seasonal trends.

- Step 3: Relate the Search Traffic to Stock Price Patterns

Here, we explore the relationship between search traffic and stock price patterns by concatenating stock price data with search data. We focus on the first half of 2020 to see if there's a correlation between search traffic and stock price during a period of market volatility.

- Step 4: Create a Time Series Model with Prophet

Finally, we set up a time series forecasting model using the Prophet library to analyze and predict patterns in the hourly search data. We visualize the forecast and identify key trends in search traffic.

# Dependencies
- Python 3.x
- pandas
- prophet
- numpy
- matplotlib

# Instructions
1. Run the Code: The code is designed to be executed in a Jupyter notebook environment. It can be run cell by cell to analyze the data step by step.

2. Data: The project uses Google search trends data and stock price data for MercadoLibre. The data is fetched from external sources and loaded into Pandas DataFrames for analysis.

3. Visualization: The project includes several visualizations to help identify patterns in the data, such as time series plots for Google search trends and stock prices.

4. Forecasting: The Prophet model is used to forecast future search trends based on historical data. The forecast includes predictions with confidence intervals, and the results are visualized for better interpretation.

# Results
Hourly Search Patterns: Identified unusual search patterns around the time MercadoLibre released its financial results.

Seasonality Analysis: Found that search traffic peaks during specific hours of the day and days of the week, with some seasonal trends evident across the year.

Stock Price Correlation: Discovered a weak correlation between search trends and stock price volatility, with no strong predictive relationship.

Prophet Forecasting: The time series model provided a forecast for search trends, with the greatest popularity seen in late nights/early mornings and the highest traffic on Tuesdays.

# Conclusion
This project demonstrates the potential of using Google search trends to analyze and forecast patterns that may relate to stock price movements. While the relationship between search traffic and stock prices is weak, the seasonal trends and forecasting models offer valuable insights for marketing and financial analysis.

# Resources
Xpert learning assistant and class work was referenced for the code in this assignment. Further Chat GPT was used to help create this readme file. And a special thanks to the educational staff that work with us daily so that I had the tools review and tackle some of these complicated tasks
