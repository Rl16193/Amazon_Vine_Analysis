# Amazon_Vine_Analysis

## Overview

Since your work with Jennifer on the SellBy project was so successful, you’ve been tasked with another, larger project: analyzing Amazon reviews written by members of the paid Amazon Vine program. The Amazon Vine program is a service that allows manufacturers and publishers to receive reviews for their products. Companies like SellBy pay a small fee to Amazon and provide products to Amazon Vine members, who are then required to publish a review.

We select the Watches dataset and use PySpark to perform the ETL process to extract the dataset, transform the data, connect to an AWS RDS instance, and load the transformed data into pgAdmin. Next, you’ll use PySpark, Pandas, or SQL to determine if there is any bias toward favorable reviews from Vine members in your dataset. Then, you’ll write a summary of the analysis for Jennifer to submit to the SellBy stakeholders.

## Results

1. Total vine reviews = 47

![image](https://user-images.githubusercontent.com/100053788/175836801-0ca0f4aa-2a3c-46d2-a74f-11dc3e479dfa.png)

2. Total paid (vine) 5-star review = 15

![image](https://user-images.githubusercontent.com/100053788/175836861-104512da-a640-4729-be75-c57d6fddbb3c.png)

3. Percentage paid 5-star review = 31.91%

![image](https://user-images.githubusercontent.com/100053788/175836878-96549b7b-72aa-41ff-85f5-cb508fe9be17.png)

4. Total regular (unpaid) review = 8362

![image](https://user-images.githubusercontent.com/100053788/175836813-7ecc70fa-27d2-48d8-9b70-c5d0a8818961.png)

5. Total regular (unpaid) 5-star review = 4332

![image](https://user-images.githubusercontent.com/100053788/175836907-e0bc979d-bc28-472b-8f0c-ba1d2d7a3f92.png)

6. Total regular (unpaid) review = 51.81%

![image](https://user-images.githubusercontent.com/100053788/175836921-ff24642b-aee3-41c6-81fa-2d50e8655f85.png)

## Summary

1. Vine-members made up less than 1% of the total reviews as well as 5-star reviews for the watches dataset.
2. Percentage 5-star reviews for Vine users are at 31.91% compared to 51.81% for regular customers.
3. As the above results show the paid customer are less likely to provide biased reviews.

In addition, running the same analysis using datasets from different product categories can provide us with the whole picture of whether reviews made by Vine members are biased.
