Rename the file: Change the filename from Home_Sales_starter_code.ipynb to Home_Sales.ipynb.

Import PySpark SQL functions: Import all necessary PySpark SQL functions needed for this task.

Load data: Read the home_sales_revised.csv file into a Spark DataFrame.

Create a temporary table: Establish a temporary table called home_sales from the DataFrame.

Answer the following using SparkSQL:

Calculate the average price of four-bedroom houses sold for each year. Ensure the result is rounded to two decimal places.
Find the average price of homes built in each year, specifically those with three bedrooms and three bathrooms. Round off the result to two decimal places.
Determine the average price of homes built in each year that have three bedrooms, three bathrooms, two floors, and a size of at least 2,000 square feet. Again, round off the result to two decimal places.
Calculate the average price of homes based on the "view" rating, where the average price is $350,000 or more. Measure the query runtime, and round the answer to two decimal places.
Cache the table: Cache the temporary home_sales table for faster access.

Verify caching: Confirm that the home_sales temporary table is cached.

Run query using cached data: Re-run the query that calculates the average price of homes by "view" rating for those priced at $350,000 or more. Measure the runtime and compare it to the runtime from the uncached version of the query.

Partition data: Partition the home sales data based on the date_built field, then format it as Parquet.

Create a temporary table: Set up a temporary table from the Parquet data.

Run the query on Parquet data: Execute the same query on the partitioned Parquet data to calculate the average price of homes by "view" rating for those priced at $350,000 or more. Compare the runtime to the uncached query.

Uncache the table: Uncache the home_sales temporary table.

Verify uncaching: Ensure that the home_sales table is no longer cached in PySpark.

Upload file to GitHub: Download the completed Home_sales.ipynb file and upload it to your "Home_Sales" GitHub repository.
