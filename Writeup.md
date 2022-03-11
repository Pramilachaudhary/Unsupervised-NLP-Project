## Improvement needed by E-commerce company in women's clothings section
Pramila Chaudhary

## Abstract:
The goal of this project is to build a topic modelling pipeline to see which areas an E-commerce company could improve for its customers.
These areas were achieved by trying different topic modeling techniques and were able to get the clear topics using NMf with TF-IDF vectorizer.

using customer's reviews from Women's Clothing E-Commerce Company

## Design:
This model is designed for E-commerce companies which can make use of this model and categorize the reviews under certain themes to extract insights from their clothing reviews. 
Because it is not easy to read thousands of reviews and it is a time consuming task. They can improve their customer experience by sorting out the issues found in historical 
clothing reviews under certain categories(topics).

## Data:
Women’s Clothing E-Commerce dataset: https://www.kaggle.com/nicapotato/womens-ecommerce-clothing-reviews
Column used for modeling 
* Review Text : String variable for the review body.
* Rating: Positive Ordinal Integer variable for the product score granted by the customer from 1 Worst, to 5 Best.

This dataset has 23486 customer reviews
and each text review has about (3 to 115)words and on average about 62 words.

## Algorithms

**Text Preprocessing:**

1. Handling Missing Data
2. Selected the subset of the review text with rating below 4 (that is 5193 reviews with rating 1,2 and 3)
3. The texts were pre-processed using Python Regular Expression (RE).
4. Using String libraries, punctuations, numbers, special characters, etc. were removed. 
5. Removed custom stop words (nltk.english + most frequent common words in English)
6. Converted all characters to lowercase
7. Applied lemmatization with NLTK

**Topic modelling:**
6. Cleaned text excerpts were then vectorized using SKLearn TFIDF and CountVectorizer packages. 
7. The term-document matrices underwent dimensionality reduction using Non-negative Matrix Factorization (NMF) or Latent Semantic Analysis (LAS, Truncated SVD) algorithms from SKLearn. 
8. After selecting the final vectorizer and topic modeler as Non-negative Matrix Factorization (NMF and TFIDFVectorizer), the topics were evaluated and interpreted using exploratory data analysis (EDA).

## Tools

* Python Pandas and Numpy for data clean, data restructuring.
* Python NLTK for text processing
* Python Scikit-learn for vectorization, topic modeling, dimensionality reduction
*  Python Matplotlib and Tableau for data visualization

## Communication:
  Uploaded the slides of the presentation on my repo and visualization on Tableau.
  
  <img width="574" alt="Screen Shot 2022-03-10 at 7 10 35 PM" src="https://user-images.githubusercontent.com/89863226/157797824-63456e12-5bdd-4e71-a664-db9e3df7f62d.png">
