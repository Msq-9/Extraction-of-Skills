# Extraction of Skills
Extracting Skills from resume using NLP & Machine Learning techniques along with Word2Vec from gensim for Word Embeddings.

## Description
Used Word2Vec from gensim for word embeddings after cleaning the data using NLP methods such as tokenization and stopword removal. Now, using these word embeddings K Clusters are created using K-Means Algorithm. Out of these K clusters some of the clusters contains skills (Tech, Non-tech & soft skills).

## Prerequisites
### Software
* PyPDF2 1.26.0
* doc2text 0.2.4
* textract 1.6.3
* python-docx 0.8.10
* pdfminer3 2018.12.3.0
* nltk 3.5
* pandas 1.0.3
* wordcloud 1.7.0
* matplotlib 3.2.1
* gensim 3.8.3
* sklearn 0.22.2.post1
* python 3.8.2
### Dataset
The dataset for this project as of now has been collected from :
https://github.com/JAIJANYANI/Automated-Resume-Screening-System
