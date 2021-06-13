# Amazon_Vine_Analysis

### Overview of the Analysis

This project analyzes Amazon reviews written by members of the paid Amazon Vine program to determine whether or not Vine members show a positivity bias in their reviews. To conduct this study, I used PySpark to extract and load the data into a PostgreSQL database hosted on AWS. I completed my final analysis of the dataset using Pandas Dataframes.

### Results

For my analysis, I selected only reviews that had 20 or more total votes, and for which the number of helpful votes were 50% or more of the number of total votes. This produced the following results:

- There were 94 Vine reviews and 40471 non-Vine Reviews.
- 48 of the 94 Vine reviews gave 5 stars. 15663 of the 40471 non-Vine reviews gave 5 stars.
- 51.1% of Vine Reviews were 5-star reviews. 38.7% of non-Vine reviews were 5-star reviews.

### Summary

There appears to be a bias toward favourable reviews from Vine members. 51.1% of Vine members awarded 5 stars in their reviews compared to only 38% of non-Vine members. It should be noted, however, that the number of Vine reviews in the dataset was relatively small, with only 94 total reviews. Further analysis could compare the average star total of Vine and non-Vine reviews.