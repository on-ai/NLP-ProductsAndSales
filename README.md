## Amazon Reviews

## This project does some text mining, and run some sentiment analysis tools. The LDA workflow is used last, it is a very powerful tool

## A simple Amazon set of files related to Magazine subscriptions is used in order to go through the entire process within a limited time

## The original project was related to the Amazon Sports and Equipments. The data would take more than 30 min to load<br>

The Amazon reviews files are public and located under <https://amazon-reviews-2023.github.io/> <br><br>

<img src="./pictures/AmazonReviewsCategories.png" alt="Desc" title="Desc Inter" width="700" height="1018"/><br><br>

The main items sold are expressed inside the Meta file<br><br>

<img src="./pictures/AmazonProductsMeta.png" alt="Desc" title="Desc Inter" width="1705" height="300"/><br><br>

The actual items sold along with the reviews are through the json, loaded into a dataframe below<br>

![Desc](./pictures/AmazonProductsReviews.png "Desc")<br><br>

# Text mining using NLTK

We are going to rely on the **nltk** package, from which we have to download some huge libraries<br>
Calling the **word_tokenize** method uses NLTK’s recommended word tokenizer, which is currently an improved TreebankWordTokenizer along with PunktSentenceTokenizer for the specified language<br>
The method returns a tokenized copy of the text, where each token is a separate word from the input text<br>
The **Sentiment Analysis** starts by identifying the positive and negative words among the words returns by the tokenizer<br>
Eventually, the **SentimentIntensityAnalyzer** is imported from nltk.sentiment. After that import, the functioning uses the Vader Sentiment metrics

# Text mining using LDA

**Text mining** extracts meaningful information from a large amount of unstructured text data<br>One of the techniques used in text mining is topic modeling, which is used to discover the hidden thematic structure in a collection of documents

## **Latent Dirichlet Allocation (LDA)** is a popular method used in topic modeling<br>It’s a three-level hierarchical generative model that uses statistical correlations between words in many documents to find and quantify the underlying subjects

## **Workflow**

**Bag of Words**: LDA treats each document as a bag of words, which means it ignores the order of words and focuses on the frequency of each word in the document<br>
**Term Frequency-Inverse Document Frequency (TF-IDF)**: LDA builds upon the concept of TF-IDF, which is a statistical measure used to evaluate the importance of a word in the context of a corpus of documents<br>
**Topic Distribution**: LDA assumes that each document is a mixture of a small number of topics and that each word’s creation is attributable to one of the document’s topics<br>
**Co-occurrence of Words**: LDA groups commonly co-occurring words into sets of topics. Each topic is modeled as a probability distribution across a vocabulary of words<br>
**Document Representation**: Each document in the collection is then represented in terms of those topics<br><br>
In essence, LDA attempts to map all the documents and the words within them to a set of hidden topics so that the words in each document are mostly captured by those imagined topics<br>It’s a powerful tool for the automatic organization, understanding, searching, and summarization of large bodies of text<br>
# Distribution of Sentiment Scores: Low-Star Reviews

![Desc](./pictures/Low-StarReviews.png "Desc Inter")<br><br>
# Distribution of Sentiment Scores: High-Star Reviews
![Desc](./pictures/High-StarReviews.png "Desc Inter")<br><br>
