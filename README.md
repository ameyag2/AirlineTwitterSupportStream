# Airline Twitter Support

## Business Summary

Natural Language Processing (NLP) is crucial in helping computers understand and interpret text and speech, much like humans do. One key application of NLP is sentiment analysis on social media, which extracts meaningful insights from platforms like Twitter. This project automates the analysis of tweets and provides automatic replies, improving customer service and engagement.

## Objective

The goal of this project is to automatically respond to customer queries on Twitter with a unique, trackable ticket ID. The replies are generated based on predicted categories of queries using deep learning models. The entire process is automated through the Tweepy API and Big Data techniques, with deployment on AWS.

<img width="748" alt="Screenshot 2024-03-18 at 3 53 09 AM" src="https://github.com/ameyagidh/AutoReplyTwitterhandle/assets/65457905/83e3d923-322e-496f-83ac-9bc0909f015c">

## Data Overview

The project uses an "airline tweets" dataset for training purposes, which includes fields such as airline names, tweet text, sentiment (positive, negative, or neutral), and topic categories (e.g., Baggage Issues, Customer Service). This dataset is pivotal for training the machine learning models used throughout the project.

## Technology Stack

- Programming Language: Python3
- Tools & Services: Confluent Kafka, Spark
- Libraries: Tweepy, Flask, Kafka, Spacy, Sklearn, Keras, Numpy, PySpark, NLTK, Matplotlib, OS

## Methodology

The process involves several key stages: data preprocessing, training sequential models like LSTMs for sentiment and topic classification, extracting named entities, and finally deploying the solution on AWS. Each stage ensures efficient tweet processing and accurate response generation.

## Code Structure

The code is divided into two main parts: Engines and Helpers. The Engines include Python scripts for tasks like training and inference, while the Helpers provide classes for tasks like preprocessing, model evaluation, and reply generation.

## Highlights

This project offers a comprehensive understanding of NLP and Big Data techniques, covering data cleaning, model training, cloud deployment, and social media API integration. It also emphasizes the benefits of automating customer support to improve interaction and satisfaction.