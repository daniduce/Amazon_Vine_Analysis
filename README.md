# Amazon_Vine_Analysis

## Overview of the analysis of the Vine program:

  Within this module we are analyzing the Amazon Vine Program, which provides a service for publishers and manufacturers to obtain reviews on their products. These reviews are published by Amazon Vine Members who use the products from companies that pay fees to Amazon. The work Jennifer and I did for the SellBy project was very successful so we have been assigned with a much bigger task which is to analyze all of the Amazon review that paid members of the Amazon Vine Program have written. 
  
 Four our dataset, we have decided to analyze the reviews for digital music. We have used PySpark on our data set to help us with the cloud ETL process of extracting, transforming and loading the data. We are creating a database in AWS RDS in order to connect our dataset tables through pgAdmin. Once our data has been extracted and transformed, we will run queries to ensure the data has been uploaded. All of these steps will help us with the process of figuring out the best and most favorable review to use from Vine Users to ensure they are not biased then submit our findings to SellBy stakeholders. 

## Results:

* How many Vine reviews and non-Vine reviews were there?
  For the question of how many reviews, I was not able to come to a final sum. 

* How many Vine reviews were 5 stars? How many non-Vine reviews were 5 stars?
  I had the same issues trying to find the total number of 5 star reviews. 

* What percentage of Vine reviews were 5 stars? What percentage of non-Vine reviews were 5 stars?
  Due to not being able to find the total number or reviews and 5 star reviews, my code would not work to find the percentage. 

## Summary:

While I was not able to find the results to the questions above, looking at the data I was able to pull through, I do not think there was positivity bias for the review in the Vine Program. One additional analysis that I would complete with the dataset is to pull through the reviews by customer id to see which customers left which type of review. This would also help take away any biased from certain users. 
