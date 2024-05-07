# London Public Transport Analysis

## Overview
This project analyzes public transport journey volume data in London using SQL queries in Snowflake. The analysis explores the popularity of different transport types, seasonal trends in Emirates Airline usage, and variations in Underground & DLR journeys over the years.

## Data Description
The data is stored in a Snowflake database called TFL with a single table called JOURNEYS, containing information about public transport journeys including the month, year, journey type, and number of journeys in millions.

## SQL Queries
The analysis involves three main SQL queries:
1. **Most Popular Transport Types:** Analyzes the total number of journeys by transport type.
2. **Emirates Airline Popularity:** Identifies the top five months and years for Emirates Airline usage.
3. **Least Popular Years for Underground & DLR:** Finds the five years with the lowest volume of Underground & DLR journeys.

## Results
The analysis reveals insights into London's public transport trends, including the dominance of buses, usage patterns of the Underground & DLR, and seasonal variations in Emirates Airline usage.

## Conclusion
The comprehensive examination of public transport data provides valuable insights for policymakers and transport authorities to optimize services and enhance the efficiency of London's transportation network.

## Tools Used
- Snowflake: For data storage and querying
- SQL: For analysis
- Markdown: For documentation

## Repository Structure
- `notebook.ipynb`: Jupyter Notebook containing the analysis code.
- `tfl_journeys_final.xlsx`: Excel file containing the dataset.
- `README.md`: This file, providing an overview of the project.
- `LICENSE`: The license for the project.

## Usage
To replicate the analysis, clone the repository and execute the SQL queries in a Snowflake environment. The Jupyter Notebook can be run to reproduce the analysis steps.



