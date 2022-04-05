# Amazon_Vine_Analysis

## Overview of the analysis

This analysis was conducted by performing the ETL process on a pet products dataset to determine whether there is bias toward favorably reviewing a pet product on Amazon if the reviewer was part of the Amazon Vine program. 

## Results

- How many Vine reviews and non-Vine reviews were there?
    - There were 170 Vine reviews.
    - There were 37,840 non-Vine reviews.

![This is a photo showing the code and results for the number of Vine reviews and the number of non-Vine reviews.](https://github.com/hmpowell/Amazon_Vine_Analysis/blob/main/Resources/Paid_vs_unpaid_count.png)

- How many Vine reviews were 5 stars? How many non-Vine reviews were 5 stars?
    - There were 65 Vine 5-star reviews.
    - There were 20,612 non-Vine 5-star reviews.

![This is a photo showing the code and results for the number of 5-star Vine reviews and the number of 5-star non-Vine reviews.](https://github.com/hmpowell/Amazon_Vine_Analysis/blob/main/Resources/5_star_reviews.png)

- What percentage of Vine reviews were 5 stars? What percentage of non-Vine reviews were 5 stars?
    - 38.2% of Vine reviews were 5 stars.
    - 54.5% of non-Vine reviews were 5 stars.

![This is a photo showing the code and results for the percentage of 5-star Vine reviews and the percentage of 5-star non-Vine reviews.](https://github.com/hmpowell/Amazon_Vine_Analysis/blob/main/Resources/Percentages.png)

## Summary

In the pet products reviews, there is not positivity bias for reviews in the Vine program. Only 38.2% of the Vine program members gave the products a 5-star review, whereas 54.5% of those not in the Vine program rated them 5 stars. If we saw positivity bias, we would expect to see a very high number of Vine members giving 5 stars and a much lower percentage of non-Vine purchasers.

Because there is no bias and the percentages for both sets of 5-star reviews are so low, I would want to do an additional analysis to find the percentage of 1- and 4-star reviews for both Vine members and non-Vine members. It may be possible to reach back out to members to find out why they did not like the products if we see a very high percentage of 1-star reviews. There may be something wrong with the products or it may be another issue. We would want to find out either way. If the majority of users chose 4 stars, it may be much less of an issue with the products.