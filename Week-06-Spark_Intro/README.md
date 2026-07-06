Week-6 Assignment - Apache Spark

Objective

The main objective of this assignment is to learn Apache Spark basics, understand Spark architecture, and perform data processing using PySpark. I also learned about transformations, actions, filtering, schema handling, and different file formats like CSV and Parquet.

Technologies Used

- Python
- PySpark
- Databricks
- CSV Dataset

Steps Performed

- Created a Spark session.
- Loaded the CSV dataset.
- Checked the schema of the dataset.
- Selected the required columns.
- Filtered the data based on conditions.
- Renamed columns and changed data types.
- Added a new column.
- Learned about transformations and actions.
- Learned the difference between CSV and Parquet.
- Tried to save the processed data as Parquet and CSV.

Challenges Faced

I was able to read and process the dataset without any issues. However, while saving the output as Parquet or CSV, I got a storage permission error in Databricks. Because of this, I could not complete the write operation. I have informed my mentor about this issue and asked for the correct writable storage path.

How I Tried to Solve It

I checked my code multiple times and verified that it was correct. Then I understood that the issue was related to the Databricks workspace and not the Spark code. I am waiting for the correct storage path from my mentor to complete this step.

What I Learned

- Basics of Apache Spark architecture.
- Difference between transformations and actions.
- How Lazy Evaluation works.
- How to filter and modify DataFrames.
- Difference between CSV and Parquet.
- Basic performance concepts like Predicate Pushdown and Shuffle.

Future Improvements

- Learn more Spark functions.
- Work with bigger datasets.
- Learn joins, aggregations, and optimization techniques.
- Build complete Spark ETL pipelines.
