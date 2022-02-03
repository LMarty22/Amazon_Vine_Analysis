# Amazon_Vine_Analysis

## Overview of the Analysis
The purpose of this project is to analyze customer reviews for Amazon products. Analysis is conducted to compare reviews provided by consumers, and consumers using the paid Amazon Vine program. Amazon Vine program pays the consumer to leave a product review. Using PySpark, Amazon RDS and pgAdmin data is extracted, transformed and loaded to further analyze data reviews on "Furniture" to determine if there is bias associated with the Vine program.

## Results

Upon competition of analysis on the reviews data provided over Furniture products below are the findings:

A new table was created in pgAdmin named "vine_table" from which data was further analyzed.
 
** Insert Data Tables in pgAdmin Link

In total the Amazon Vine Program produced 136 reviews, while 18,019 reviews were provided by unpaid consumers.
** Insert Image Total Count Paid vs Unpaid

In this step total five star reviews are counted, in order to demonstrate the relationship between paid consumer reviews and unpaid consumer reviews.  
** Insert Image Total Count Paid vs UnPaid FIVE Star Reviews


Further this data is analyzed on percentage basis. From this it is gathered that the five star paid Vine Program Reviews are a 54% representation of all paid reviews provided, and five star unpaid reviews represent about 47% of all provided unpaid reviews. 

** Insert Image Percentage paid vs UnPaid Five Star Reviews

## Summary
When comparing the paid Vine Program reviews to the unpaid consumer reviews, there is a slight bias for the paid reviews to provided "Five Stars". However the bias is marginal upon examining the total number of reviews provided in the unpaid category vs paid category. The volume at which reviews are provided by the unpaid consumer are much greater, which tends to be more reliable in predicting future customer experience with the product type "Furniture". An additional analysis which could be done to further dissect the data, is to identify the timing of the paid five star reviews vs the unpaid five star reviews. The timing of the paid reviews would indicate if the Vine Program is working and is attracting consumers to the product using the provided reviews and it would further highlight the value or discount the program effectiveness. 



