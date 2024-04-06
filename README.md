# Home_Sales_Analysis

Using SparkSQL, I was able to create a temporary table and answer the following queries related to home sales:

What is the average price for a four-bedroom house sold for each year? 

What is the average price of a home for each year the home was built, that has three bedrooms and three bathrooms? 

What is the average price of a home for each year the home was built, that has three bedrooms, three bathrooms, two floors, and is greater than or equal to 2,000 square feet? 

What is the average price of a home per "view" rating having an average home price greater than or equal to $350,000? Determine the run time for this query, and round off your answer to two decimal places.

I cached the table and partitioned it by 'date_built' on the parquet data and created a temporary table for the parquet data. Finally, I uncached the table.

