# Improvement needed by E-commerce company in certain areas

## Question:
I am going to use customer's reviews from Women's Clothing E-Commerce Company to build an unsupervised learning model 
to do analysis and topic modeling to see which areas E-commerce company could improve for its customer.

## Dataset:

Women’s Clothing E-Commerce dataset:
https://www.kaggle.com/nicapotato/womens-ecommerce-clothing-reviews

column used for modeling 
**Review Text** : String variable for the review body.

**Rating:** Positive Ordinal Integer variable for the product score granted by the customer from 1 Worst, to 5 Best.


After preprocessing a E-commerce company customer's reviews I selected the subset of the review text with rating below 4.
I built an LDA model using sklearn with a base model of 4 topics using Tfdif. Tuned the hyper parameters of the Tfdif to be max_df = 0.5, 
                                min_df = 0.05
                             
