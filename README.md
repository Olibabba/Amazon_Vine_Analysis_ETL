# Amazon_Vine_Analysis

## Overview
My team has been tasked with performing an analysis on the Amazon Vine program for signs of positivity bias. The Amazon Vine program is a service that allows manufacturers and publishers to receive reviews for their products. Companies pay a small fee to Amazon and provide products to Amazon Vine members, who are then required to publish a review.

We will choose a category at random and discover the proportion of 5 star reviews given by Vine members compared to non-vine members.

The reviews are supplied by Amazon here:
https://s3.amazonaws.com/amazon-reviews-pds/tsv/index.txt

The choosen category is outdoors:
https://s3.amazonaws.com/amazon-reviews-pds/tsv/amazon_reviews_us_Outdoors_v1_00.tsv.gz

## Results

As you can see below, at 107, there were not many Vine reviews in this data set, and 52% of those were 5 stars.

- 56 5 star reviews from Vine members
- 107 total reviews
- 52% 5 star reviews

![Ratings from Vine members](https://github.com/Olibabba/Amazon_Vine_Analysis/blob/main/resources/Screen%20Shot%202022-07-15%20at%2010.22.44%20PM.png)

There were many more reviews from non-Vine members.

- 21005 5 star ratings
- 39869 reviews from
- 53% 5 star reviews

![Ratings from non-vine members](https://github.com/Olibabba/Amazon_Vine_Analysis/blob/main/resources/Screen%20Shot%202022-07-15%20at%2010.22.36%20PM.png)

## Summary

Though the number of non-vine reviews was far higher, at 52% and 53% the proportion of five star reviews was almost identical between Vine reviews and non-Vine reviews.

This is a strong sign that there is not positivity bias among Vine members.

In order to further analize this possibility, we could repeat the analasis on a broader subsection or even all reviews, not just those with a certain number of votes, or those considered helpful.

A quick check shows that there are 3137 total Vine reviews. So increasing our subsection from 107 at all would significatnly broaded the scope of our analysis and provide deeper insight into the rating habits of Vine members.