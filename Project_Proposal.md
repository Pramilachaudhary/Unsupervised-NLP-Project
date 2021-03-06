# Project Proposal of Unsupervised Learning Project

## Question:
I am going to use customer's reviews from Women's Clothing E-Commerce Company to build an unsupervised learning model 
to do analysis and topic modeling to see which areas E-commerce company could improve for its customers for example: topics like  “positive reviews”, “negative reviews”, “reviews about fit”, “reviews about quality”, etc.

## Dataset:

Women’s Clothing E-Commerce dataset:
https://www.kaggle.com/nicapotato/womens-ecommerce-clothing-reviews

## Data Description:

This dataset includes **23486 rows and 10 feature variables**. Each row corresponds to a customer review, and includes the variables:

Clothing ID: Integer Categorical variable that refers to the specific piece being reviewed.

Age: Positive Integer variable of the reviewers age.

Title: String variable for the title of the review.

**Review Text:** String variable for the review body.

Rating: Positive Ordinal Integer variable for the product score granted by the customer from 1 Worst, to 5 Best.

Recommended IND: Binary variable stating where the customer recommends the product where 1 is recommended, 0 is not recommended.

Positive Feedback Count: Positive Integer documenting the number of other customers who found this review positive.

Division Name: Categorical name of the product high level division.

Department Name: Categorical name of the product department name.

Class Name: Categorical name of the product class name.

## Tools:

Python Pandas and Numpy for data clean, exploratory data analysis and feature engineering.

Python NLTK, spaCy and Scikit-learn for text processing

## MVP Goal:
EDA and Preprocessed with a topic modeling technique applied on customer reviews.
