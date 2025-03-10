# Sentiment Analysis on App Reviews

## Overview
This project focuses on performing sentiment analysis on app reviews. The goal is to preprocess the review data, analyze the sentiment, and visualize the distribution of sentiments. The project is implemented in a Jupyter Notebook and uses Python libraries such as Pandas, Matplotlib, Seaborn, and Scikit-learn.

## Project Structure
The project is divided into several key steps:

1. **Data Loading**: The dataset containing app reviews is loaded into a Pandas DataFrame.

2. **Text Preprocessing**: The text data is cleaned and preprocessed using various techniques such as removing mentions, hashtags, URLs, numbers, and punctuation. The text is also tokenized, filtered for stopwords, and stemmed.

3. **Sentiment Labeling**: The reviews are labeled based on their scores. Reviews with scores of 1-2 are labeled as "negative", 3 as "neutral", and 4-5 as "positive".

4. **Exploratory Data Analysis**: The distribution of sentiment labels is visualized using a count plot.

5. **Label Encoding**: The sentiment labels are encoded into numerical values for further analysis.

6. **Word Cloud Visualization**: Word clouds are generated for each sentiment category to visualize the most common words.

## Requirements
To run this notebook, you need the following Python libraries:

- Pandas
- Matplotlib
- Seaborn
- Scikit-learn
- WordCloud
- Sastrawi (for Indonesian text preprocessing)


