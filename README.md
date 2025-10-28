# DataAnalysts-DataScientists-project
Query language project
# STRUCTURED QUERY LANGUAGE
This is the overview of this repo.
This repo is designed as a structured SQL class where students will be assigned practical SQL-related tasks to enhance their understanding and proficiency

## TASK SUBMISSION AND DOCUMENTATION GUILDLINES
Students are expected to submit their SQL task files in this section, ensuring each submission is properly documented and committed with clear, descriptive messages.

### STANDARD QUERY FORMAT AND SYNTAX
This section outlines the best practices for writing SQL queries, including formatting, naming conventions, and optimization tips for clarity and efficiency.
And this is how we should endeavor to write our queries and commands.

```SQL
SELECT *
FROM emptable
WHERE language = 'Love'
;
```
### Finance data description

1. Symbol:  The stock ticker symbol. In this case, it's always BAJAUTOFIN, referring to Bajaj Auto Finance.
2. Series:  Market segment or category of the stock. For equities traded in India, EQ indicates "Equity" segment (regular shares).
3. Date:    The trading date for that row. Format: DD-MMM-YYYY.
4. Prev Close:  The closing price of the stock from the previous trading day. Used to assess price movement compared to the previous day.
5. Open Price:   The price at which the first trade was executed on that trading day.
6. High Price:         The maximum price the stock reached during that day’s trading session.
7. Low Price:          The minimum price the stock touched during the day.
8. Last Price:        The last recorded trade price before the market closed that day.
9. Close Price:       The final or closing price of the stock, typically used in financial analysis. This is the price at the end of regular trading hours.
10. Average Price:      The volume-weighted average price (VWAP) of all trades for that day. Calculated as:(Turnover/TotalTradedQuantity)(Turnover / Total Traded Quantity)(Turnover/TotalTradedQuantity)
11. Turnover           The total value of shares traded during the day in Indian Rupees (₹). Calculated as: TotalTradedQuantity×AveragePriceTotal Traded Quantity × Average PriceTotalTradedQuantity×AveragePrice
12. No. of Trades:       Number of separate transactions (buy-sell orders) executed that day. In this dataset, it's often shown as - meaning data not available or not reported.

## Objectives for the Finanace
1. Which days saw the stock open lower than the previous day’s close but close higher than it opened?
2. Find the dates when the stock price reached or exceeded ₹1000 during the day.
3. On which days did the stock trade fewer than 1,000 units but still record a turnover above ₹50,000?
4. Identify all dates where the daily price range (high minus low) exceeded ₹100.
5. What were the top 5 highest closing prices across all years, and on which days did they occur?
6. List the 10 days with the lowest trading volume (quantity), sorted from lowest to highest.
7. Which trading days had the largest absolute difference between opening and closing prices
8. What is the average closing price for each year?
9. Calculate the total number of shares traded each year.
10. Which year had the highest average turnover per trading day?
11. For each year, find the day with the highest intraday price (High Price).
12. Group by month and find the average “Close Price” for each.
13. Find the years where the average traded quantity was below 5,000.
14. Which months had an average close price above ₹500?
15. Which trading day had the highest average price across the entire dataset?
16. Find all trading days where the turnover exceeded the average turnover of all days.
17. How many trading days occurred in each quarter of the year?
18. Which month had the most trading days in the year 2020?

## Heathcare data description
1. ID: A unique identifier assigned to each individual or record.
2. Name: The full name of the individual.
3. Age: The age of the individual (in years).
4. Gender: The gender of the individual (e.g., Male, Female, Other).
5. City: The city where the individual resides.
6. Blood Type: The blood group of the individual (e.g., A+, B-, O+).
7. Education: The highest level of education attained by the individual (e.g., High School, Bachelor’s, Master’s).
8. Employment Status: The individual’s current employment status (e.g., Employed, Unemployed, Student).
9. Salary: The individual’s annual or monthly salary (in monetary units).
10. Health Condition: A description of the individual’s overall health condition (e.g., Excellent, Good, Poor).
11. Credit Score: A numerical representation of the individual’s creditworthiness (e.g., 720, N/A).
12. Date of Admission: The date the individual was admitted to a hospital or

## Healthcare Objectives
You are hired as a Data Analytics Consultant in a healthcare system. Your primary responsibility is to analyze and clean messy data related to patients' health records. This involves identifying and addressing inconsistencies, missing values, and formatting errors, all of which are commonly encountered in real-world datasets.
This Data Cleaning Challenge is designed to help you enhance your critical thinking, attention to detail, and problem-solving skills while working with real-world messy data.
Perform exploratory data analysis (EDA) to understand the dataset’s structure, identify anomalies, and gain preliminary insights.
### Tasks
- Clean and prepare the data for further analysis, ensuring it is consistent, accurate, and ready for use.
Document your cleaning process, detailing:
1. The steps taken.
2. The logic behind each decision.
3. Any assumptions made during the cleaning process.
4. Any limitations of the cleaned data.
- Identify cities or demographics with higher healthcare needs based on health conditions and admission dates.

