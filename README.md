# Walmart-Sales-Data
# Walmart Sales Data Analysis
This project provides an analysis of Walmart sales data by using SQL to filter, aggregate, and manipulate data, revealing valuable insights into sales performance, customer behavior, and product trends.

## Key Findings and Insights:
Data Exploration

1: The dataset contains detailed sales information, including product categories, sales quantities, customer demographics (city, gender, etc.), and transactional data such as payment methods and dates. The initial overview of the dataset helped establish the structure and range of information available.
Branch and City-Specific Sales

2: Sales data was filtered by different branches to identify trends at specific locations. For instance, data for Branch A was examined independently, revealing localized sales performance. Additionally, city-specific filtering showed how gender demographics varied in different cities. For example, male customers were analyzed in the city of Naypyitaw to compare their shopping habits with other regions.
Advanced Filtering and Conditions

3: Sales were filtered based on multiple conditions, such as customers in Yangon who paid in cash, or sales records excluding specific branches like Branch B. This allowed for a more targeted analysis to compare performance across cities, payment methods, and store branches.
Product Quantities and Ratings

4: The analysis identified the maximum quantity sold in a single transaction, providing insights into bulk purchases. Additionally, the lowest customer rating and the average rating were calculated, offering a measure of customer satisfaction across different transactions.
Sales and Pricing Statistics

5:Total sales were summed up to get an overall view of revenue generation, and the average unit price of products sold was calculated. This gave a financial snapshot of the business's performance and allowed for pricing strategy evaluations.
Date and Time Analysis

6: Sales data was broken down by various time components like day, month, and year. This enabled a trend analysis to observe how sales fluctuated across different days of the week, months, and seasons. Understanding these patterns helped pinpoint peak sales periods.
Customer and Product Information

7: The customer information was refined by concatenating details such as city, branch, and gender, creating a clear view of customer demographics. This streamlined the process of profiling customers based on their location and behavior. Additionally, product lines like "Sports and travel" were specifically analyzed, and sales were filtered to exclude this category when necessary, revealing insights into category-specific performance.
Top-Selling Transactions

8: The analysis highlighted the top 10 highest-grossing sales, revealing which transactions contributed most to revenue. This helps identify popular products or high-value customers.
Gender-Based Analysis

9: Sales data was grouped by gender, showing how many male and female customers were involved in the transactions. This gender-based analysis provided insights into which gender contributed more to the sales for Walmart.
Pagination for Large Data Handling

10: To manage the large dataset, pagination techniques were used to analyze specific segments of the data. This allowed the analysis to focus on smaller chunks of data without overwhelming resources.
Unique Customer Ratings

11: The number of distinct customer ratings was counted to understand the diversity in feedback. This metric is crucial for analyzing customer satisfaction trends and identifying how many unique ratings contributed to the overall perception of Walmart’s services.
Pattern Matching and Customer Data

12: Pattern matching was applied to identify specific types of customers or transactions, such as searching for invoice IDs that contain certain digits or finding payment methods that start with a specific letter. This helped categorize and isolate specific customer behaviors for more detailed analysis.
