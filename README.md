# Zomato Dataset Analysis

This project performs an in-depth analysis of restaurant data from the Zomato platform, focusing on key metrics such as ratings, customer reviews, and restaurant types. The analysis uses Python and SQLite for data handling, cleaning, and visualization.

## Overview

1. **Data Collection**:
   - Data is loaded from an SQLite database, containing detailed information about restaurants in Bengaluru, India.

2. **Data Cleaning**:
   - Missing values are addressed by replacing placeholders like `NEW` or `-` with appropriate values or `NaN`.
   - Columns with complex formats (e.g., ratings with `/5`) are parsed and standardized.

3. **Exploratory Data Analysis**:
   - Insights into restaurant types, cuisines, ratings, cost distribution, and more.
   - Visualization of key metrics using Matplotlib and Seaborn.

4. **Feature Engineering**:
   - Categories such as `online_order`, `book_table`, and `approx_cost` are analyzed for trends.
   - Reviews and votes are aggregated for deeper insights.

## Data Features

- **Columns Analyzed**:
  - `name`: Name of the restaurant.
  - `address`: Address in Bengaluru.
  - `rate`: Overall rating out of 5.
  - `votes`: Total number of ratings.
  - `online_order`: Availability of online ordering.
  - `book_table`: Option for table booking.
  - `cuisines`: Types of food served.
  - `approx_cost`: Estimated cost for two people.

## Libraries Used

- **Data Handling**: `pandas`, `numpy`
- **Database Connection**: `sqlite3`
- **Visualization**: `matplotlib`, `seaborn`

## Results

- Insights into popular cuisines and dining preferences in Bengaluru.
- Identification of factors influencing restaurant ratings and votes.
- Visualization of cost distribution and its correlation with ratings.

