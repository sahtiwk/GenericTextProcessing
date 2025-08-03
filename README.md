# Twitter Text Processing and Feature Engineering

This repository contains a Jupyter Notebook detailing a comprehensive workflow for cleaning, preprocessing, and engineering features from a raw Twitter dataset. The project serves as a practical guide to the essential steps required before applying machine learning models to text data.

## Project Overview

The notebook takes a dataset of 4,000 tweets with sentiment labels and applies a series of transformation techniques to clean the text and extract meaningful features. The goal is to transform unstructured text data into a structured format suitable for analysis and modeling.

## Key Techniques Covered:

* **Basic Feature Engineering**:
    * Word, character, and average word length counts.
    * Counting stopwords, hashtags, mentions, and numeric characters.
* **Text Cleaning & Normalization**:
    * Converting text to lowercase.
    * Expanding contractions (e.g., "don't" -> "do not").
    * Removing punctuation, special characters, and extra spaces.
    * Removing HTML tags and accented characters.
* **Advanced NLP Preprocessing**:
    * Stopword removal using spaCy's built-in list.
    * Lemmatization to reduce words to their base form.
    * Identifying and removing the most common and rarest words to reduce noise.
* **Visualization**:
    * Generating a WordCloud to visualize the most frequent words in the processed text.

## Libraries Used

* Pandas
* spaCy
* TextBlob
* NLTK
* WordCloud
* Matplotlib
