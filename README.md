# SMS Spam Classifier

## Overview

This repository contains a project for building a SMS spam classifier using the Multinomial Naive Bayes algorithm. The classifier is trained on a dataset obtained from Kaggle, which consists of SMS messages labeled as either spam or ham (non-spam).

- **Project URL**: [Demo](https://smsspamclassifier00byatharv-tb5bdjabgslg9dicqffw7u.streamlit.app/) 
- **Data Source**: [Kaggle SMS Spam Collection Dataset](https://www.kaggle.com/datasets/uciml/sms-spam-collection-dataset)

## Project Details

- **Algorithm**: Multinomial Naive Bayes
- **Text Preprocessing**: TF-IDF vectorization from NLTK
- **Deployment**: Streamlit web application

## Description

In this project, I developed a SMS spam classifier using the Multinomial Naive Bayes algorithm. The classifier is trained on a dataset obtained from Kaggle, which contains SMS messages labeled as either spam or ham. The dataset, although slightly old, provides a good foundation for understanding and implementing text classification techniques.
The model performs well on older-style spam messages but may have slightly lower accuracy and precision when dealing with newer spam messages. This is due to the evolving nature of spam messages and changes in language usage over time.

### Learning Experience

Throughout this project, I gained a deeper understanding of how the algorithms used work, particularly Multinomial Naive Bayes for text classification. Additionally, I learned about the importance of data preprocessing techniques such as TF-IDF vectorization for improving model performance.

## Libraries Used

- NLTK
- Streamlit
- Scikit-learn
- Pandas
- NumPy


