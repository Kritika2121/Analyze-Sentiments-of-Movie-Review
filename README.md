# Sentiment Analysis of Movie Reviews

## Overview
This project performs sentiment analysis on movie reviews using machine learning techniques. The primary goal is to classify movie reviews as positive or negative based on their textual content. The dataset used is the IMDB dataset, which contains labeled movie reviews, allowing for effective training and evaluation of the models.

## Background
Sentiment analysis is a crucial aspect of Natural Language Processing (NLP) that involves determining the emotional tone behind a body of text. In the context of movie reviews, it helps in understanding public opinion about films and can be valuable for movie producers, marketers, and researchers.

The IMDB dataset contains a large number of movie reviews, each labeled with a sentiment (positive or negative). This project utilizes various machine learning algorithms to analyze the reviews and predict their sentiment, providing insights into which factors contribute to a movie being perceived positively or negatively.

## Methodology
1. **Data Collection**: The IMDB dataset is utilized, which consists of 50,000 reviews—25,000 labeled for training and 25,000 for testing.
  
2. **Data Preprocessing**:
   - Cleaning the text data by removing special characters, URLs, and stop words.
   - Tokenizing the text and converting it to lowercase.
   - Performing stemming or lemmatization to reduce words to their base form.

3. **Feature Extraction**:
   - Utilizing techniques like Bag of Words or TF-IDF (Term Frequency-Inverse Document Frequency) to convert text data into numerical format suitable for machine learning models.

4. **Model Training**:
   - Implementing various machine learning algorithms such as Logistic Regression, Naive Bayes,to classify the reviews.
   - Evaluating model performance using metrics like accuracy, precision, recall, and F1-score.

5. **Visualization**:
   - Creating visualizations to display the distribution of sentiments and other relevant insights using libraries like Matplotlib and Seaborn.

## Requirements
To run this project, you need to have the following packages installed:

- pandas
- numpy
- seaborn
- matplotlib
- scikit-learn
- nltk

You can install the requirements by running:
```bash
pip install -r requirements.txt
