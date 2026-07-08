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

While working on the assignment, I initially faced an issue while saving the DataFrame as Parquet and CSV because the default workspace location was not writable. After discussing the issue with my mentor, I created and used a Databricks Volume as the storage location. This resolved the issue, and I was able to save the output files successfully.

How I Resolved It
Identified that the error was related to the storage location and not the Spark code.
Explored the available storage options in the Databricks workspace.
Created and used a Databricks Volume (spark_volume) as the writable location.
Successfully saved the processed data in both Parquet and CSV formats.

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
