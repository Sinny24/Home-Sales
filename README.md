# Home-Sales
1. Rename the file "Home_Sales_starter_code.ipynb" as "Home_Sales.ipynb."

2. Import the necessary PySpark SQL functions for the assignment.

3. Read the data from the "home_sales_revised.csv" file in the starter code into a Spark DataFrame.

4. Create a temporary table called "home_sales."

5. Answer the following questions using SparkSQL:

a. Find the average price of four-bedroom houses sold each year and round the answer to two decimal places.

b. Determine the average price of homes built each year with three bedrooms and three bathrooms, rounded to two decimal places.

c. Calculate the average price of homes each year with three bedrooms, three bathrooms, two floors, and a size greater than or equal to 2,000 square feet, rounded to two decimal places.

d. Determine the "view" rating for homes priced at or above $350,000 and record the query runtime, rounded to two decimal places.

6. Cache the temporary table "home_sales."

7. Check if the temporary table "home_sales" is cached.

8. Using the cached data, run a query that filters out view ratings for homes with an average price greater than or equal to $350,000. Record the runtime and compare it to the uncached runtime.

9. Partition the formatted parquet home sales data by the "date_built" field.

10. Create a temporary table for the parquet data.

11. Run the query that filters out view ratings for homes with an average price greater than or equal to $350,000 using the parquet data. Record the runtime and compare it to the uncached runtime.

12. Uncache the temporary table "home_sales."

13. Verify that the temporary table "home_sales" is uncached using PySpark.

14. Download the "Home_Sales.ipynb" file and upload it to your "Home_Sales" GitHub repository.
