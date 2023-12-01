# TFIDF-KMeans
NLP pipeline for unsupervised topic modeling of news headlines using TF-IDF vectorization and k-means clustering

The code demonstrates an NLP pipeline for unsupervised topic modeling of news headlines. It first loads a dataset of news headlines and does some NLP preprocessing like lowercasing, removing punctuation and stopwords, and lemmatization. I then leverage common NLP techniques like TF-IDF vectorization to numerically represent the text. TF-IDF converts the preprocessed headlines into vectors indicating the importance of words within each headline and across the corpus.

After the NLP preprocessing and vectorization steps, the code then clusters the TF-IDF headline vectors using k-means, which is an unsupervised machine learning approach commonly used in NLP for topic modeling. Analyzing the clusters and cluster centers gives a glimpse into the main topics present across the new headlines based solely on the headline text itself, without needing manual topic labels.

