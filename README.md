# Amazon Vine Analysis

Analyzing bias of reviews of the Vine Amazon review program using PySpark, Pandas, and SQL. 

## Overview

The following analysis reviewed Amazon customer reviews for home products, including organic reviews, as well as reviews that were incentivized using the Amazing Vine program. Do the users who received these home products for free from Amazon tend to leave more positive reviews? By attempting to answer this question we can see the validity and fairness of this Vine program for consumers and merchants. 

To complete this analysis, we used the following tools:
* Amazon Web Services Relational Database, connected to PgAdmin
* Amazon review data pulled into PgAdmin via PySpark and Google Colab
* Jupyter Notebook and python/pandas to further clean and analyze the data

## Results:

Vine Review Stats:
* 1448 reviews total
* 647 5-star reviews
* 5-star reviews made up 45%

![Total Vine Reviews]("Resources/total_vine_reviews.PNG)

Organic (non-vine) Review Stats:
* 90768 reviews total
* 44104 5-star reviews
* 5-star reviews made up 49%

![Total Non Vine Reviews]("Resources/total_non_vine_reviews.PNG)

Final Analysis:
![Vine Analysis]("Resources/Vine_Analysis_Results.PNG)

## Summary

In conclusion, the Vine program for the home good products for sale on Amazon does not impact the positive or negative bias of product reviews. According to the analysis, the non-vine, or organic reviews showed a higher percentage of 5-star reviews. 

In order for there to be proven bias from the Vine program for positive reviews, we would have seen a much higher percentage of 5-star reviews from the Vine program. However, the percentages of 5-star reviews were very similar: 45% of the vine program, and 49% of the organic reviews were 5-star. 

Additional analysis is recommended on the percentage of other 1, 2, 3, and 4 star reviews to see if similar percentages appear from both groups. It is still possible that the Vine reviwers overall left more favorable reviews without looking at the other star values. 