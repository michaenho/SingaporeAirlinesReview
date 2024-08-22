# SingaporeAirlinesReview

###### Author: Michaen Ho

### Project Overview

For this project, we will make use of Natural Language Processing (NLP) and machine learning to perform sentiment analysis based on customer reviews from the Singapore Airlines. This could help provide further insights into customer satisfaction and service quality provided by the airline.

### Dataset

The dataset is sourced from [Kaggle](https://www.kaggle.com/datasets/kanchana1990/singapore-airlines-reviews). It contains 10000 anonymized customer reviews, providing a broad perspective on the passenger experience with Singapore Airlines. It has features such as review title and text, satisfaction rating and also the number of helpful votes. All personal identifiers have been removed to ensure ethical standards.

### Sentiment Analysis

Sentiment analysis is the process of analyzing digital text to determine if the emotional tone of the message is positive, negative, or neutral. Singapore Airlines could do this form of analysis to help them improve their product offerings by learning what works and what doesn't based on customer reviews. 

### Word2Vec

In this project, I am using Word2Vec to convert the text data into vectors that are suitable for training by the machine learning models. Word2Vec is a powerful technique in NLP that turns words into vectors, which are essentially numerical representations that capture the meanings of words in a way that computers can understand. Unlike traditional methods like Bag of Words (BoW) and Term Frequency-Inverse Document Frequency (TF-IDF), which treat words as isolated and independent, Word2Vec understands that words exist in a context.

In BoW and TF-IDF, words are represented based on their frequency within a document, but this ignores the semantic relationships between words. For example, "cat" and "kitten" are treated as entirely unrelated. Word2Vec, on the other hand, considers the context in which words appear, allowing it to capture deeper relationships, such as similarities or analogies (e.g., "king" is to "queen" as "man" is to "woman").

This contextual understanding makes Word2Vec a more sophisticated and effective method for tasks like semantic analysis, where understanding the relationships between words is crucial.








