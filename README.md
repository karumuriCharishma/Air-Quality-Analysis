# Air Quality Analysis of Indian Cities (2015-2020)

## Objective
Analyse daily air quality data from 26 Indian cities to find which cities
and seasons have the worst air, and how AQI changed over time.

## Tools
Python (pandas, matplotlib), SQL (SQLite), Kaggle Notebooks

## Dataset
Air Quality Data in India (2015-2020), Kaggle, by Rohan Rao

## Steps
1. Loaded and explored the data (29,531 rows, 16 columns)
2. Cleaned it: converted dates, removed rows with no AQI, removed AQI above 500
3. Created Year, Month and Season columns
4. Answered questions with SQL queries
5. Visualised results with matplotlib

## Key Findings
- Winter has the highest average AQI (about 204), monsoon the lowest (about 109)
- Ahmedabad, Delhi, Patna, Gurugram and Lucknow had the highest average AQI
- Comparing the same cities and months, AQI was roughly flat from 2015 to 2019
  and dropped sharply in 2020

## Limitations
- Cities cover different time periods
- About 400 Ahmedabad readings above 500 were removed as invalid
- 2020 data is partial, and the drop coincides with the COVID lockdown

## Link
Kaggle notebook: [https://www.kaggle.com/code/karumuricharishma/air-quality-analysis]
