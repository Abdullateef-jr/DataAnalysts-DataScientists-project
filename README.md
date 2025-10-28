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
