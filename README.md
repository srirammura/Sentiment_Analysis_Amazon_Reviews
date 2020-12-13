# Sentiment Analysis Amazon Reviews

## Problem Statement
   
  There are two datasets that you are given:
  
   1) Review dataset which has user-product review information
   2) Product metadata for the products present in #1

## Outcomes:

 1) Out of all the users, find the global potential promoter(A promoter is the one who mostly has positive words to say about a product and hence believed to act as a promoter of the product. A global promoter would be someone who is a promoter for maximum number of products)

 2) Out of all the products, find the product which has most number of promoters

## Dataset description:

###  Review Dataset

 1) reviewerID - ID of the reviewer, e.g. A2SUAM1J3GNN3B 
 2) asin - ID of the product, e.g. 0000013714 
 3) reviewerName - name of the reviewer 
 4) vote - helpful votes of the review 
 5) style - a dictionary of the product metadata, e.g., "Format" is "Hardcover" 
 6) reviewText - text of the review 
 7) overall - rating of the product 
 8) summary - summary of the review 
 9) unixReviewTime - time of the review (unix time) 
10) reviewTime - time of the review (raw) 
11) image - images that users post after they have received the product
 
### Product Metadata

 1) asin - ID of the product, e.g. 0000031852
 2) title - name of the product
 3) feature - bullet-point format features of the product
 4) description - description of the product
 5) price - price in US dollars (at time of crawl)
 6) image - url of the product image
 7) related - related products (also bought, also viewed, bought together, buy after viewing)
 8) salesRank - sales rank information
 9) brand - brand name
10) categories - list of categories the product belongs to
11) tech1 - the first technical detail table of the product
12) tech2 - the second technical detail table of the product
12) similar - similar product table
