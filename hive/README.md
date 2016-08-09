# Hive Exercises

## Try Tutorial

 The first thing that you should do is to try the following tutorial
 http://hortonworks.com/hadoop-tutorial/how-to-process-data-with-apache-hive/
 
## Test different storing formats
 On our local cluster we have already create a table called **users**. It's a dump from
 StackExchange. In Hive you can store your table in different formats. Try to create two 
 tables with different storage like: Parquet (https://parquet.apache.org/), CSV. Which format requires
 less space to be stored? 
  
## Try simple queries
 Analyze the performance of simple queries like (make sure that you check both version of table):
    
    1. Select **display_name** by **id**
    2. Select **reputation** by **display_name**
    3. Find the user with most **views**
    4. Find the oldest registered 10 users that are still active
    5. Find reputation distribution by age
    6. Number of users that are living in New York. 
  
 
## Investigate join performance
 For this another table is used **badges**.
 
    1. Find the badges for a user specified by its **display_name**
    2. Find the average reputation of a user for a certain badge
    3. Find the user with the highest reputation that has less than 10 badges   
    
## Investigate whether is possible to improve the joins performance.
  Hint: Maybe you need another data model.