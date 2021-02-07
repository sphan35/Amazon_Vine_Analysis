# Amazon_Vine_Analysis

## Overiew of the Amazon_Vine_Analysis

- The purpose of this analysis was utilizing tools as Google Colab and PySpark to handle large datasets and enter the world of Big Data. Using PySpark allowed for a in-depth understanding of the relationship between a cloud database such as Amazon Web Services(AWS) and a open source database such as Postgres have in working together to compute cloud storage data into a database. Understanding this relationship and the capabilities to process large data from cloud storage, allowed for the challenge of analyzing an Amazon customer reviews through various methods such as Pandas, PySparks, and Postgres to create a dataframe extracted from the datasets stored on AWS RDS database. 

## Results 
- Based off the Amazon data set I chose, "https://s3.amazonaws.com/amazon-reviews-pds/tsv/amazon_reviews_us_Video_Games_v1_00.tsv.gz", the results of the number of Vine and non-Vine reviews was astonishing. From my dataframes and data analysis, there were zero Vine (paid-program) reviews. All of the reviews were non-Vine(unpaid program) reviews, and that totaled out to be 145,431 reviews. I am as shocked as you are and I had to double check my code was correct. The image below show my results.

- There was a total of 80,677 5-star ratings from the Amazon reviews of U.S. Video Games. All of those 80,677 5-star ratings were non-Vine.

- As previously mentioned, with there being 0 Vine reviews, 0% of the five-star rating were Vine reviews. Therefore, 100% of the 5-star rating were non-Vine reviews.
