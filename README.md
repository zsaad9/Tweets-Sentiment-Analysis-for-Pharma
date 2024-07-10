#Tweets Sentiment Analysis on Pfizer and BioNTech

Overview
This project involves analyzing the sentiment of tweets related to Pfizer and BioNTech vaccines using Natural Language Processing (NLP) techniques. The goal is to gain insights into public perception and sentiment regarding these vaccines.

Project Structure

Loading the Data:

The dataset is loaded from a Google Drive link.
Initial data exploration includes displaying the first few rows and understanding the structure, data types, and missing values.

Initial Data Exploration:

Display the structure and summary of the dataset.
Check for missing values and the number of unique values in each column.
Drop unnecessary columns such as is_retweet.

Data Cleaning:

Clean the text data by removing URLs, stopwords, and special characters using regular expressions and NLTK.
Convert the cleaned text to lowercase for consistency.

Sentiment Analysis:

Use VADER (Valence Aware Dictionary and sEntiment Reasoner) from NLTK for initial sentiment analysis.
Classify tweets into positive, negative, and neutral sentiments based on sentiment scores.

Model Training:

Train machine learning models such as Convolutional Neural Networks (CNN), Naive Bayes, and Support Vector Machines (SVM) on the cleaned text data.
Evaluate and compare the performance of different models, with CNN yielding the best results.

Results Visualization:

Visualize the distribution of sentiments using various plots (e.g., bar charts, pie charts).
Analyze and interpret the results to understand the overall sentiment towards Pfizer and BioNTech vaccines.
