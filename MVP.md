# Improvement needed by E-commerce company in certain areas

## Question:
I am going to use customer's reviews from Women's Clothing E-Commerce Company to build an unsupervised learning model 
to do analysis and topic modeling to see which areas E-commerce company could improve for its customer.

## Dataset:

Women’s Clothing E-Commerce dataset:
https://www.kaggle.com/nicapotato/womens-ecommerce-clothing-reviews

Column used for modeling 
**Review Text** : String variable for the review body.

**Rating:** Positive Ordinal Integer variable for the product score granted by the customer from 1 Worst, to 5 Best.

## Method:

After preprocessing a E-commerce company customer's reviews I selected the subset of the review text with rating below 4.
I built an LDA model using sklearn with a base model of 4 topics using Tfdif. Tuned the hyper parameters of the Tfdif to be max_df = 0.5 and  min_df = 0.05

Here are the 4 topics with top ten terms:
Topic1 : is about clothe size complains.
Topic2 : is about fabric quality.
Topic3 : is about meterial design.
Topic4 : is about fittinf issues.


![topics](https://user-images.githubusercontent.com/89863226/157132911-728e5685-e695-43ad-93b0-b539fc3b3b38.png)
