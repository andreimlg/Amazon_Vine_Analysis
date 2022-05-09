# Amazon_Vine_Analysis

## Overview of the analysis: Explain the purpose of this analysis.
This module helped us undestand how Big Data is organized through all the web and how to perform analysis and ETL processes using cloud services, such as AWS. 
The challenge that we are facing now is that the amount of data generated overpasses the physical capacities to be managed in a traditional way without incurring in high costs for preparation and maintenance.

As part of being presented with a solution to this challenge, we were given the task to analyze a database on amazon products' reviews using AWS, POSTGRES and PySpark.
For the first part of this challenge we were able to use data from the web, transform it and load it into a new database. These are the tables used:

![customers_table](https://user-images.githubusercontent.com/31755703/167364280-5b20c0c0-9323-4c20-a549-fa81121b4a0c.PNG)
![products_table](https://user-images.githubusercontent.com/31755703/167364300-21b7a297-e5b1-493b-9cc3-ecf70963a23a.PNG)
![review_id_table](https://user-images.githubusercontent.com/31755703/167364306-5c8228a8-0e53-4b8a-b2b9-722ca89cd9ed.PNG)
![vine_table](https://user-images.githubusercontent.com/31755703/167364317-dd2f4384-e978-4903-997e-3910874fdba8.PNG)


## Results: Using bulleted lists and images of DataFrames as support, address the following questions:
For the second deliverable we got deeper into the database (the database I chose was Mobile Electronics) to answer the following questions:
## How many Vine reviews and non-Vine reviews were there?
### of paid reviews: 4
### of unpaid reviews: 1064

## How many Vine reviews were 5 stars? How many non-Vine reviews were 5 stars?
Five Star paid reviews: 1
Five Star unpaid reviews: 527

## What percentage of Vine reviews were 5 stars? What percentage of non-Vine reviews were 5 stars?
% of Five Star paid reviews: 25.00%
% of Five Star unpaid reviews: 49.53%



## Summary: In your summary, state if there is any positivity bias for reviews in the Vine program. Use the results of your analysis to support your statement. Then, provide one additional analysis that you could do with the dataset to support your statement.

As per the results shown:
% of Five Star paid reviews: 25.00%
% of Five Star unpaid reviews: 49.53%
There is no positive bias for Vine reviews. We need to remember that this may change from one category to another. As well as taking into account that the previous filters made to the database can change the perspective of this result.

The additional analysis we can perform is to make this analysis through all the categories presented (some t tests can be run in order to determine if between categories there is a significance difference), and determining a new criteria for helpful votes in order to include more data. Probably this will arise more questions and we may need to make different hypothesis (specifying a significance level according to this study).





