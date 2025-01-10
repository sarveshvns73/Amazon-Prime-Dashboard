# Amazon Prime Dashboard

## Description
This project is an interactive Power BI dashboard designed to visualize and analyze Amazon Prime data, focusing on content distribution, trends, and ratings. It aims to provide insights into key business metrics and user preferences.

## Features
- Interactive filters for year, genre, and region.
- Visualization of total content count, genre distribution, and top-rated shows.
- Trend analysis of content production over the years.

## Dataset
The dataset includes metadata of Amazon Prime video content, such as:
- Title
- Genre
- Year of release
- IMDb rating
- Runtime  

## Data Preparation
- Removed duplicate entries.
- Handled missing IMDb ratings by replacing them with the average.
- Standardized date formats.
- Performed data transformation to ensure compatibility with Power BI.

## Dashboard Overview
The dashboard contains three main sections:
1. Overview: Displays total content count and average ratings.
2. Genre Insights: Analyzes content distribution by genre.
3. Trends: Visualizes year-wise trends in content production.

## Insights Derived
- Comedy and Drama are the most common genres.
- The average IMDb rating is 7.2.
- Content production peaked in 2020, showing a significant increase in recent years.

## Technology Stack
- Power BI
- Microsoft Excel (for data cleaning)
- Python (for advanced preprocessing)

## How to Use
1. Download and install Power BI Desktop.
2. Clone this repository.
3. Open the `Amazon Prime Dashboard.pbix` file in Power BI.
4. Use the interactive filters to explore the data.

## Future Scope
- Integrate live data updates.
- Add user behavior analytics.
- Include predictive models for content trends.

## Acknowledgments
Thanks to the data providers and resources that supported this project. Special thanks to Power BI tutorials for guidance.
