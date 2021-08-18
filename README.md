# Fake News Detection with Python and Machine Learning
This is a Fake news detection project using Machine Learning, check the above Notebook for more.


## What is Fake News?

Fake news is false or misleading information presented as news. It often has the aim of damaging the reputation of a person or entity, or making money through advertising revenue. However, the term does not have a fixed definition, and has been applied more roadly to include any type of false information, including unintentional and unconscious mechanisms, and also by high-profile individuals to apply to any news unfavourable to his/her personal perspectives.


## Problem Statement:

Given a news csv file, build a model that accurately classifies a piece of news as real or fake.

## What is TfidfVectorizer?

The term tf–idf stands for term frequency–inverse document frequency, it is a mathematical statistic that is planned to reflect how significant a word is to a record in a collection or corpus.

TF (Term Frequency): The number of times a word appears in a document is its Term Frequency. A higher value means a term appears more often than others, and so, the document is a good match when the term is part of the search terms.

IDF (Inverse Document Frequency): Words that occur many times a document, but also occur many times in many others, may be irrelevant. IDF is a measure of how significant a term is in the entire corpus.

The TfidfVectorizer converts a collection of raw documents into a matrix of TF-IDF features.

## PassiveAggressiveClassifier

The Passive-Aggressive algorithms are a family of Machine learning algorithms, they are generally used for large-scale learning. It is one of the few ‘online-learning algorithms‘. In online machine learning algorithms, the input data comes in sequential order and the machine learning model is updated step-by-step, as opposed to batch learning, where the entire training dataset is used at once. This is very useful in situations where there is a huge amount of data and it is computationally infeasible to train the entire dataset because of the sheer size of the data.

## The results:

Accuracy Score of Passive Aggressive Classifier: 93.76%, the confusion matrix is [[590  38]
                                                                                [ 41 598]]
With this model there are 590 true positives, 598 true negatives, 38 false positives and 41 false negatives.
