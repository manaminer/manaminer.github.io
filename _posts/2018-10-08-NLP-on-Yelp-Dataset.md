---
title: "Machine Learning Project: NLP"
date: 2018-10-08
tags: [machine learning , data science , simple project , beginner , nlp , natural language processing , tfidf]
excerpt: "Machine Learning , NLP , natural language processing , TfIdf "
---

# Simple NLP project

## Using a Dataset from Yelp:

The Dataset in this NLP project we will be attempting to classify Yelp Reviews into 1 star or 5 star categories based off the text content in the reviews.

Each observation in this dataset is a review of a particular business by a particular user.

Also:

* The "stars" column is the number of stars (1 through 5) assigned by the reviewer to the business. (Higher stars is better.) In other words, it is the rating of the business by the person who wrote the review.

* The "cool" column is the number of "cool" votes this review received from other Yelp users.

* The "useful" and "funny" columns are similar to the "cool" column.

### The link to the Github repository[HERE](https://github.com/manaminer/NLP-YELP)

#### Doing some Exploratory Data Analysis

<img src="{{ site.url }}{{ site.baseurl }}/images/art1/art1heatmap.png" alt="">

## Conclusion
Making two models:
* 1st with ordinary train_test_split then fitting to Naive Bayes Algorithm which gave results of 92% accuracy.
* 2nd with implementing Pipeline tuples with same steps in 1st model plus adding Tfidf Transformer which gave results of 66% accuracy and incorrect model.

So in this project Tfidf Transformer wasn't the best choice to use.

Yet you can clone the project from [HERE](https://github.com/manaminer/NLP-YELP) and try other methods !
