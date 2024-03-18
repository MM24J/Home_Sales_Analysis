# Home_Sales

Using SparkSQL, I was able to create a temporary table and answer the following queries:

What is the average price for a four-bedroom house sold for each year? Round off your answer to two decimal places.

What is the average price of a home for each year the home was built, that has three bedrooms and three bathrooms? Round off your answer to two decimal places.

What is the average price of a home for each year the home was built, that has three bedrooms, three bathrooms, two floors, and is greater than or equal to 2,000 square feet? Round off your answer to two decimal places.

What is the average price of a home per "view" rating having an average home price greater than or equal to $350,000? Determine the run time for this query, and round off your answer to two decimal places.

I cached the table and partitioned it by 'date_built' on the parquet data and created a temporary table for the parquet data. Finally, I uncached the table.

Note: I was able to complete the challenge utilizing the activities we did in class on this topic as a reference and using Stack Overflow and Google for a few errors I encountered. I looked at the SQL documentation to review a few concepts.
