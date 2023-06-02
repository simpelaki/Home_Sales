# Home_Sales


# Information
From the home sales data, I created a Spark DataFrame and then to a temparary DataFrame where we can apply SQL queries to answer the questions. Next, I cached the DataFrame to check the speed the query result. We can see that query result returns faster than the original query using the memory process when caching. We then test the speed with partitioned data. In this case, the partitioned data was not as quick as the original or cached DataFrame.

# Technologies Used
* Google Colab
* PySpark
* SQL
