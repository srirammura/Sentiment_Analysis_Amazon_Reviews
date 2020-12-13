# Sentiment Analysis Amazon Reviews

## Problem Statement:

There are two datasets that you are given.
Review dataset which has user-product review information
Product metadata for the products present in #1

## Outcomes Expected :

 1) Out of all the users, find the global potential promoter(A promoter is the one who mostly has positive words to say about a product and hence believed to act as a promoter of the product. A global promoter would be someone who is a promoter for maximum number of products)

 2)Out of all the products, find the product which has most number of promoters

## Dataset description:

### 1. Review Dataset

reviewerID - ID of the reviewer, e.g. A2SUAM1J3GNN3B
asin - ID of the product, e.g. 0000013714
reviewerName - name of the reviewer
vote - helpful votes of the review
style - a dictionary of the product metadata, e.g., "Format" is "Hardcover"
reviewText - text of the review
overall - rating of the product
summary - summary of the review
unixReviewTime - time of the review (unix time)
reviewTime - time of the review (raw)
image - images that users post after they have received the product
 
### 2. Product Metadata

asin - ID of the product, e.g. 0000031852
title - name of the product
feature - bullet-point format features of the product
description - description of the product
price - price in US dollars (at time of crawl)
image - url of the product image
related - related products (also bought, also viewed, bought together, buy after viewing)
salesRank - sales rank information
brand - brand name
categories - list of categories the product belongs to
tech1 - the first technical detail table of the product
tech2 - the second technical detail table of the product
similar - similar product table
