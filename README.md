# Amazon_Vine_Analysis
## Project Overview
**Project Task:** The Amazon Vine program is a service that allows manufacturers and publishers to receive reviews for their products. Companies like SellBy pay a small fee to Amazon and provide products to Amazon Vine members, who are then required to publish a review. We will analyze Amazon reviews written by members of the paid Amazon Vine program to determine if having a paid Vine review makes a difference in the percentage of 5-star reviews.

**Technical Steps:** Use PySpark to perform the ETL process to extract the dataset, transform the data, connect to an AWS RDS instance, and load the transformed data into pgAdmin. Then PySpark, Pandas, or SQL to determine if there is any bias toward favorable reviews from Vine members in the dataset.
* Deliverable 1: Perform ETL on Amazon Product Reviews:
    * View the ETL Process in a Google Colaboraty Notebook [Here](https://github.com/Angienoelhaverly/Amazon_Vine_Analysis/blob/main/Amazon_Reviews_ETL.ipynb)
* Deliverable 2: Determine Bias of Vine Reviews
    * View the Vine Reviews Bias Analysis [Here](https://github.com/Angienoelhaverly/Amazon_Vine_Analysis/blob/main/Vine_Review_Analysis.ipynb)

## Results
* How many Vine reviews and non-Vine reviews were there?
    * 170 Vine Reviews
    * 37,823 Non_Vine Reviews
    * ![q1](https://user-images.githubusercontent.com/73972332/112770130-fd94e180-8fd9-11eb-82b3-8c39763af392.png)
* How many Vine reviews were 5 stars? How many non-Vine reviews were 5 stars?
    * 65 Vine Reviews were 5 Stars
    * 20,605 Non_Vine Reviews were 5 Stars
    * ![q2](https://user-images.githubusercontent.com/73972332/112770134-0dacc100-8fda-11eb-9789-40798935fb7f.png)
*  What percentage of Vine reviews were 5 stars? What percentage of non-Vine reviews were 5 stars?
    *  38.24% of Vinew Reviews were 5 Stars. 
    *  54.48% of Non-Vine Reviews were 5 Stars. 
    *  ![q3](https://user-images.githubusercontent.com/73972332/112770155-2fa64380-8fda-11eb-8f89-d28a0eae36a4.png)

## Analysis
