# Module22

Introduction
This is an overview of the Spark DataFrame assignment, outlining the tasks to be completed and the associated point values. 
The assignment involves working with a dataset related to home sales and performing various operations using Apache Spark

This assignment included the following steps: 
A Spark DataFrame was created from the given home sales dataset. This forms the base for subsequent analysis.
A temporary table named "home_sales" was created from the original DataFrame. This temporary table will be used for executing SQL queries.
A SQL query was written to retrieve the average price, rounded to two decimal places, for four-bedroom houses sold in each year.
A SQL query was formulated to obtain the average price, rounded to two decimal places, for homes featuring three bedrooms and three bathrooms.
A SQL query was constructed to determine the average price of homes with three bedrooms, three bathrooms, two floors, and a size greater than or equal to 2,000 square feet for each year built, rounded to two decimal places.
A SQL query was developed to calculate the view rating for the average price of homes equal to or exceeding $350,000. 
The "home_sales" temporary table was cached, and its validation is performed to ensure successful caching.
The query from Task 6 was executed on the cached "home_sales" table, and the runtime is computed.
A partition of the home sales dataset was created based on the "date_built" field, and the formatted parquet data is read.
A temporary table was generated from the parquet data, setting the stage for executing SQL queries.
The "home_sales" temporary table is uncached, and its integrity is verified to ensure proper uncaching.



