# BERT for Text Classification

> This was an exercise in using Bidirectional Transformers for Language Understanding (BERT) for binary text classification with TensorFlow. 



## General info

BERT has revolutionised the area of natural language processing as a highly efficient transformer pretrained on massive amounts of data. However, utilising it can feel daunting. This project was an exercise to learn about and try out BERT on a [Quora dataset](https://www.kaggle.com/c/quora-insincere-questions-classification/data) consisting of over one million questions. These questions are labelled as either 'Sincere' or 'Insincere'. This code explored how to make the dataset compatable with BERT and create a model to achieve the above task on a validation dataset. 

The data was preprocessed and tokenised for BERT classification. After this, a TensorFlow input pipeline is created, and a BERT model for text classification is trained and evaluated.  



## Technologies

Python 3.7.10 (w/ TensorFlow 2.3.0)



## Inspiration

This project is inspired by the Coursera Project Network.
