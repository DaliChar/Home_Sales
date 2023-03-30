# Module 22 : Big Data Home Sales Challenge
![main pic readme](https://user-images.githubusercontent.com/112433621/228697206-f2cd9138-4bb0-4d94-a97f-2c120b95f7f2.jpg)

-photo by Thirdman

## Instructions
Rename the Home_Sales_starter_code.ipynb file as Home_Sales.ipynb.

Import the necessary PySpark SQL functions for this assignment.

_ Read the home_sales_revised.csv data in the starter code into a Spark DataFrame.

- Create a temporary table called home_sales.

- Answer the following questions using SparkSQL:

- What is the average price for a four-bedroom house sold for each year? Round off your answer to two decimal places.

- What is the average price of a home for each year it was built that has three bedrooms and three bathrooms? Round off your answer to two decimal places.

- What is the average price of a home for each year that has three bedrooms, three bathrooms, two floors, and is greater than or equal to 2,000 square feet? Round off your answer to two decimal places.

- What is the "view" rating for homes costing more than or equal to $350,000? Determine the run time for this query, and round off your answer to two decimal places.

- Cache your temporary table home_sales.

- Check if your temporary table is cached.

- Using the cached data, run the query that filters out the view ratings with an average price of greater than or equal to $350,000. Determine the runtime and compare it to uncached runtime.

- Partition by the "date_built" field on the formatted parquet home sales data.

- Create a temporary table for the parquet data.

- Run the query that filters out the view ratings with an average price of greater than or equal to $350,000. Determine the runtime and compare it to uncached -runtime.

- Uncache the home_sales temporary table.

- Verify that the home_sales temporary table is uncached using PySpark.

## Support and Resources
- The first part of the challenge was quite straight forward becasue we had done something similar in class(with Varun).
- First challenge was incooperating the decimal point requirement to the code without breaking it. I tried several ways and in the end I asked the tutor during class and they gave me good guidance(This was Eduardo). 

- for the sql comparison operator I tried == but that returned an empty table and > was returning an error so I used geeksforgeeks.org for a reminder.
- My main points of refence were the following class activities
1- spark_dates_solved_colab.ipynb
2 - Flight_Delays_Cached_solved_colab.ipynb
3- Practicing_Partitions_solved_colab.ipynb

Reviewing these activities sort of helped me get an idea or the requirements for the challenge.
![pexels-pnw-production-8250916](https://user-images.githubusercontent.com/112433621/228697789-ceb25eae-75cf-4de2-965d-ded956c56a88.jpg)

-photo by pnw_productions
