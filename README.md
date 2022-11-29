# Amazon-Vine-Analysis

## Overview

The overarching purpose of this project was to conduct a meta-analysis of Amazon reviews. Specifically it was to analyze reviews produced as part of the Amazon Vine program, where select members of Amazon's reviewer community are compensated to review sample products. The primary goal of this inquiry is to determine if there is any bias towards favorable reviews from the paid Vine members in the available data.

Out of the 50 datasets of product categories available to chose from, I chose to analyze reviews in the Camera category - high-value, technical products requiring experience and knowledge to effectively review. The initial ETL portion of the project was conducted, as proscribed, using AWS, postgresql, and PySpark in Google Colab. The data analysis segment was conducted using PySpark and Google Colab.

## Results

We first reviewed how many Vine reviews, and non-Vine reviews there were.

![img1](https://github.com/bikachuuuuuu/Amazon-Vine-Analysis/blob/main/Resources/img1.png)

![img2](https://github.com/bikachuuuuuu/Amazon-Vine-Analysis/blob/main/Resources/img2.png)

As we can see, there is a drastic difference between the two. There are thousands of reviews that are outside of the Vine program, and less than 100 for the Vine program.

Next, let us investigate how many of the Vine reviews were 5 stars, versus how many non-Vine reviews were 5 stars.

![img3](https://github.com/bikachuuuuuu/Amazon-Vine-Analysis/blob/main/Resources/img3.png)

![img4](https://github.com/bikachuuuuuu/Amazon-Vine-Analysis/blob/main/Resources/img4.png)


We can see that there are still thousands of reviews for those outside the Vine program, and fewer for the Vine program.

With this data provided, we calculated the percentages of how many Vine reviews were 5 stars, and how many non-Vine reviews were 5 stars.

![img5](https://github.com/bikachuuuuuu/Amazon-Vine-Analysis/blob/main/Resources/img5.png)

Percentages of the 5 star reviews.

For the Vine program, 51.1% of reviews were 5 stars. Outside of the Vine program, 38.7% of reviews were 5 stars.

## Conclusion

What these numbers seems to suggest is that there is not strong bias toward five-star reviews from paid Amazon Vine reviewers. If anything, Vine reviews might show a tendency towards being more critical in their reviews. This conclusion could be further examined by looking at the distribution of all star-levels across paid and unpaid reviews. Also, for a more thorough analysis, this same meta-analysis should be conducted across a few different product catagories.
