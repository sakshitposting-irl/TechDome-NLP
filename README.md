# README
## !! IMPORTANT !!

# Text Analysis Project

This repository contains a Python script for performing text analysis on a dataset of news articles. The script utilizes various natural language processing (NLP) techniques and libraries to preprocess the text data, perform sentiment analysis, topic modeling, and visualize the results.

## Features

- **Text Preprocessing**: The script cleans the text data by removing stop words, lemmatizing words, and converting them to lowercase.
- **Sentiment Analysis**: The sentiment polarity of each article is calculated using the SpaCy TextBlob library, and the sentiment is categorized as positive, negative, or neutral.
- **Topic Modeling**: The Latent Dirichlet Allocation (LDA) algorithm from the Gensim library is used to identify topics present in the articles. The script provides a function to assign meaningful names to the topics based on the top words.
- **Topic Visualization**: The frequency of each identified topic across the articles is visualized using a bar chart created with Matplotlib and Seaborn.

## Requirements

To run the script, you need to have the following Python libraries installed:

- pandas
- numpy
- spacy
- nltk
- spacy-textblob
- transformers
- gensim
- matplotlib
- seaborn

You can install the required libraries using pip:

```
pip install pandas numpy spacy nltk spacy-textblob transformers gensim matplotlib seaborn
```

Additionally, you need to download the necessary NLTK data files by running the following commands within the script:

```python
nltk.download('punkt')
nltk.download('stopwords')
nltk.download('wordnet')
```
## Example

The script includes an example usage where it analyzes a dataset of technology news articles. It performs sentiment analysis, topic modeling, and visualizes the frequency of identified topics.
