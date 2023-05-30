# Amazon_Product_Review_and_Rating_Analysis# Amazon Product Review Analysis with NBC Classifier

This project aims to analyze a large dataset of Amazon product reviews and ratings using Natural Language Processing (NLP) techniques and a Naive Bayes Classifier (NBC). The goal is to develop a predictive model that can accurately identify factors influencing product ratings and reviews.

## Overview
The project involves scraping approximately 5000 reviews and their corresponding ratings (ranging from 1 to 5) from Amazon for a chosen product. These reviews will be used as the training data for the NBC classifier. Reviews rated 1 or 2 will be considered as 'negative', while ratings of 4 or 5 will be categorized as 'positive'.

## Key Highlights
- **NBC Classifier**: The Naive Bayes Classifier is a probabilistic machine learning algorithm widely used for text classification tasks. It leverages the Bayes' theorem and assumes independence between features. In this project, the NBC classifier will be trained to predict the sentiment of product reviews based on the textual content.
- **NLP Fundamentals**: Natural Language Processing techniques will be employed to preprocess and analyze the text data. This includes tasks such as tokenization, stop word removal, stemming, and feature extraction. These steps help in transforming raw text into a format suitable for the NBC classifier.
- **Python and SQL**: The project will utilize Python programming language for data scraping, preprocessing, and model development. SQL will be used to handle and manage the collected data efficiently.
- **Data Visualization**: Insights and trends in the dataset will be identified using data visualization tools like Tableau and Power BI. Visualizations will aid in understanding the distribution of ratings, identifying common words in positive and negative reviews, and uncovering patterns in the data.
- **Predictive Model**: A predictive model will be built using machine learning algorithms and NLP fundamentals. The model's primary objective is to accurately predict the sentiment (positive or negative) of a given review based on its content. The model's performance will be evaluated using appropriate metrics, aiming for a high accuracy level.

## Project Outcomes
- An NBC classifier capable of categorizing product reviews as positive or negative based on their textual content.
- Insights and trends visualized using data visualization tools, highlighting factors influencing product ratings and reviews.
- A predictive model with a high level of accuracy (approximately 88%) in identifying the sentiment of product reviews.

The project's code and resources will be made available on GitHub, providing a comprehensive guide to reproduce the analysis and potentially extend it to other products or domains. The repository will include the data scraping code, NLP preprocessing techniques, NBC classifier implementation, data visualization scripts, and a detailed README with instructions for running the code and interpreting the results.

By leveraging NLP techniques and a robust NBC classifier, this project aims to uncover valuable insights into factors impacting product ratings and reviews on Amazon.

## License
The code and resources in this repository are provided under the [MIT License](LICENSE). Feel free to use and modify the code for academic, research, or commercial purposes. Please refer to the license file for more details.

We hope this project provides a valuable resource for age detection using deep learning techniques. Enjoy exploring and experimenting with the models!

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)