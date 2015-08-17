****This repository contains programs related to MapReduce, Cassandra, Spark,Scala,Mahout************

***Input dataset used is : Yelp academic dataset. URL: https://www.yelp.com/academic_dataset

Programs perform the following functions:

1) PGM-1: Using MapReduce

Q 1 a: Count the total number of reviews,
Q 1 b: Count total number of users
Q 1 c: Count total number of business entities in the data.csv file.

This demonstrates the use of MapReduce to filter and count data.


2) PGM-2: Using MapReduce

Find the top ten rated businesses using the average ratings.
*The star column represents the rating.

Please answer the question by calculating the average ratings given to each business using the
review entity rows. Do not use the already calculated ratings (average_stars) contained in the
business entity rows.

3) PGM-3: Using Cassandra

Using Cassandra CQL3, write commands to do the following:
1- Create a table for this dataset. Use (business_id) as the Primary Key.
2- Load all records in the dataset to this table.
3- Select the tuple which has business id 'axPZazfSZFnynOV52mbe2Q'
4- Delete all rows in the table.
5- Drop the table.

4) PGM-4: Using SCALA

Given input address(any part of the address e.g., city or state), find all
the business ids located at the address. You must take the input address in the
command line. [For example, if the input address is Stanford then you need to
find all businesses with stanford in the address column] [You only need
business3.csv file to get the answer.]

5) PGM-5: Using SCALA

List the business_id of the Top 10 businesses using the average ratings. This
will require you to use review3.csv.

6) PGM-6: Using MAHOUT & SPARK-ITEMSIMILARITY

Read the following link related to co-occurrence based recommendation system
implemented in mahout.

https://mahout.apache.org/users/algorithms/intro-cooccurrence-spark.html

Currently Mahout switched from MapReduce to Apache Spark. It has an interactive
shell (showed in the class, lecture contains how to install it). Using that, apply itembased
collaborative filtering using mahout’s spark-itemsimilarity.
The review3.csv contains ratings for each business. Using businesses
rated as 4 by the users, recommend other businesses, a user may be
interested in. For each business, show maximum of 5
recommended businesses”


