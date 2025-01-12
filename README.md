# Home Sales Analysis Using SparkSQL

## Project Overview
This project utilizes Apache Spark and SparkSQL to analyze a dataset containing information about home sales. Key tasks include creating temporary views, partitioning data, and utilizing caching to optimize query performance. 

### Objectives
- Analyze home sales data to compute average prices based on various criteria.
- Use SparkSQL for data manipulation and querying.
- Optimize queries using caching and partitioning techniques.

## Files
- **Home_Sales.ipynb**: Jupyter notebook containing all the SparkSQL queries and analysis.
- **home_sales_revised.csv**: Dataset file used for the analysis.

## Instructions
1. **Rename** the starter notebook to `Home_Sales.ipynb`.
2. **Import necessary libraries** and modules for SparkSQL.
3. **Load the dataset** into a Spark DataFrame and create a temporary view called `home_sales`.
4. **Execute SQL queries** to answer the following:
   - Average price of four-bedroom houses sold each year.
   - Average price of homes per year built, with specific attributes like number of bedrooms and bathrooms.
   - Analysis based on the `view` rating with price thresholds.
5. **Cache the temporary table** `home_sales` and verify its caching status.
6. **Partition the data** by the `date_built` field and create a formatted Parquet file.
7. **Create and use temporary tables** for both the raw and partitioned data.
8. **Compare query performance** on cached and uncached data.
9. **Uncache** the temporary table and verify it has been uncached.


## Key Learnings
- Learned how to efficiently use SparkSQL for complex data querying.
- Gained experience in optimizing Spark data processing workflows with caching and partitioning.
- Enhanced understanding of the Spark execution and optimization model.

## Tools and Resources Used
- [Stack Overflow](https://stackoverflow.com/questions/tagged/apache-spark): Questions and answers on a wide range of Spark related topics.
- [Apache Spark Documentation](https://spark.apache.org/docs/latest/): Official documentation for Apache Spark, providing in-depth information on setup, configuration, and APIs.
- [PySpark Documentation](https://spark.apache.org/docs/latest/api/python/): Detailed guide and API reference for PySpark, useful for Python users working with Spark.
- **Apache Spark**: For data processing and SQL querying.
- **PySpark**: Python API for Spark.
- **Jupyter Notebook**: For interactive development and testing.

## Conclusion
This project demonstrates the power of Spark and SparkSQL in handling large datasets for real estate analytics. The use of caching and partitioning significantly improved the performance of data retrieval operations.

