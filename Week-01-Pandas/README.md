# Week 1 Assignment

This is my Week 1 assignment submitted as part of the CEI Data Engineering Fellowship.

The dataset provided for this task was not available as a single CSV file. Instead, it was divided into multiple category based files. Before starting the analysis, I combined all the CSV files into one dataset so that the cleaning and exploration process could be done in a single place.

After loading the data into Pandas, I explored the dataset using different functions such as head(), tail(), shape(), columns and info() to get a better understanding of the data.

I then checked for missing values and reviewed the overall quality of the dataset. Duplicate records were also verified and no duplicate rows were found in the combined dataset.

As part of the assignment requirements, I performed basic data operations such as selecting columns and filtering records based on conditions.

I also created a derived column called popularity_score using the product rating and ratings count. The purpose of this column was to get a simple measure of how popular a product is based on both customer ratings and review volume.

Once the exploration and cleaning steps were completed, the final dataset was exported as a new CSV file for future use.

## Challenges Faced
The main challenge in this assignment was that the dataset was not available as a single CSV file. , I first had to understand how the files were organized before combining them into one dataset.
Another small challenge was working with file paths in Databricks. Initially, I had a few issues while locating the uploaded files, but after verifying the folder structure and paths, I was able to load all the datasets successfully.
Although these issues took some time to figure out, they helped me better understand how data is stored and accessed in a real working environment.

## Key Learnings
Through this assignment, I gained hands-on experience with Pandas, data exploration, data cleaning, working with multiple files, and creating derived features from existing data.

## Files included in this folder:
1. Assignment Notebook (.ipynb)
2. Cleaned Dataset (.csv)
3. README.md

## Tools used:
Python
Pandas
Databricks
GitHub
