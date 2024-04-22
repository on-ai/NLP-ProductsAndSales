'# Amazon Reviews' 
# This project does some text mining, and run some sentiment analysis tools. The LDA workflow is used last, it is a very powerful tool
# A simple Amazon set of files related to Magazine subscriptions is used in order to go through the entire process within a limited time
# The original project was related to the Amazon Sports and Equipments. The data would take more than 30 min to load


# Text mining using LDA

## **Text mining** extracts meaningful information from a large amount of unstructured text data<br>One of the techniques used in text mining is topic modeling, which is used to discover the hidden thematic structure in a collection of documents

## **Latent Dirichlet Allocation (LDA)** is a popular method used in topic modeling<br>It’s a three-level hierarchical generative model that uses statistical correlations between words in many documents to find and quantify the underlying subjects

## **Workflow**

**Bag of Words**: LDA treats each document as a bag of words, which means it ignores the order of words and focuses on the frequency of each word in the document<br>
**Term Frequency-Inverse Document Frequency (TF-IDF)**: LDA builds upon the concept of TF-IDF, which is a statistical measure used to evaluate the importance of a word in the context of a corpus of documents<br>
**Topic Distribution**: LDA assumes that each document is a mixture of a small number of topics and that each word’s creation is attributable to one of the document’s topics<br>
**Co-occurrence of Words**: LDA groups commonly co-occurring words into sets of topics. Each topic is modeled as a probability distribution across a vocabulary of words<br>
**Document Representation**: Each document in the collection is then represented in terms of those topics<br><br>
In essence, LDA attempts to map all the documents and the words within them to a set of hidden topics so that the words in each document are mostly captured by those imagined topics<br>It’s a powerful tool for the automatic organization, understanding, searching, and summarization of large bodies of text
