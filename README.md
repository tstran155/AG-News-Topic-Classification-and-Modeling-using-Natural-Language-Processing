# AG's news topic classification and modeling using Natural Language Processing (NLP)

AG's corpus of news articles is a collection of more than 1 million news articles. News articles have been gathered from more than 2000  news sources by ComeToMyHead in more than 1 year of activity. ComeToMyHead is an academic news search engine which has been running since July, 2004. The dataset is provided by the academic community for research purposes in data mining (clustering, classification, etc), information retrieval (ranking, search, etc), xml, data compression, data streaming, and any other non-commercial activity. 

This dataset is constructed by Xiang Zhang (*) from the database above. The AG's news topic classification dataset is constructed by choosing 4 largest classes from the original corpus. Each class contains 30,000 training samples and 1,900 testing samples. The total number of training samples is 120,000 and testing 7,600. The file classes.txt contains a list of classes corresponding to each label.

Topic modeling and text classification are two popular techniques in NLP that deal with analyzing and organizing large volumes of text data. Topic modeling is an unsupervised technique aimed at discovering hidden topics within a collection of documents, while text classification is a supervised technique that assigns predefined categories to text documents.

There are two notebooks in this repository and their structures are similar, except for Sections #4.

1. Prepare Problem

a) Load libraries

b) Load dataset

2. Exploratory Data Analysis

a) Descriptive statistics

b) Text length analysis

c) Word frequency analysis

d) N-gram analysis

3. Prepare Data

a) Data preprocessing

b) Split data into train and test sets

4. Topic Classification and Modeling

Notebook 1: AG's News Topic Classification using SVM, RF, and LSTM models¶

Notebook 2: AG's News Topic Modeling using Latent Dirichlet Allocation (LDA)

5. Conclusions

-------------------------------------------------------------------------------------------------------------------------------------
Reference
(*) Xiang Zhang, Junbo Zhao, Yann LeCun. 2015.  Character-level Convolutional Networks for Text Classification. Proceedings in Advances in Neural Information Processing Systems 28 (NIPS 2015). https://papers.nips.cc/paper_files/paper/2015.
