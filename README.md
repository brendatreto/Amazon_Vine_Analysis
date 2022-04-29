# Amazon_Vine_Analysis

## Overview
The purpose of this project was to analyze the Amazon Vine program, extract, transform and load the data using Pyspark and pgAdmin and determine if there are more favorable results from Vine members.
By connecting to AWS RDS we were able to calculate the different metrics that would allow us to make and informed report

We worked with reviews for books.

### Software
- Google Colab Notebook
- PostreSQL 11.5
- pgAdmin 4
- AWS

## Results
- How many Vine reviews and non-Vine reviews were there?

*Fig 1. Vine reviews vs non-Vine reviews*

![paid_unpaid_vine](https://user-images.githubusercontent.com/22451540/165871377-e548dfe6-7788-44d4-b1bb-36919b22ed36.PNG)


- How many Vine reviews were 5 stars? How many non-Vine reviews were 5 stars?

*Fig 2. 5 stars vine vs 5 stars non-Vine*

![five_star_comparison](https://user-images.githubusercontent.com/22451540/165871458-1d023480-3d81-4748-9a6f-7442622441cc.PNG)


- What percentage of Vine reviews were 5 stars? What percentage of non-Vine reviews were 5 stars?
**Note:** Because there were no 5 stars paid reviews the percentage was not able to be estimated

*Fig 3. Percentage of 5 star Vine reviews vs 5 stars non-Vine reviews*

![stars_percentage](https://user-images.githubusercontent.com/22451540/165871583-9e168fe5-31c8-4809-8fdc-504a80be99a7.PNG)


## Summary
Because of the way the information was shaped we are not able to detect wheather bias exists in the data. So far, we are only able to tell that 60.14% of the reviews are non-Vine reviews. Even without the information from vine reviews, we can infer that this will not describe a positive bias for Vine reviews in the program. 

To deepen our research we could use a different breaking point (other than 20 reviews) to see if this broadens the scope of our information
