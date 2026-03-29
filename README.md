# News Classification using Machine Learning

## Overview
This project builds a machine learning model to classify news articles into categories based on their textual content. The goal is to explore how natural language processing (NLP) techniques can be used to automatically understand and organize large collections of text data.

## Research Question
Can machine learning models effectively classify news articles into broader categories based on textual content?

## Dataset
The dataset used is the AG News dataset, accessed via the Hugging Face datasets library.

It contains news articles categorized into four classes:
- World
- Sports
- Business
- Sci/Tech

For this project, the task is simplified into a binary classification problem by grouping the original four categories into two broader classes.

The original four classes are grouped into two categories by combining labels 0–1 into one class and labels 2–3 into another.

## Method
- Text preprocessing using TF-IDF vectorization
- Train-test split (80/20)
- Logistic Regression classifier

## Results
The model achieves high accuracy (0.935) in classifying news articles into two grouped categories.

Some errors occur due to ambiguity and overlap between categories, but overall performance is strong. The high accuracy suggests that even simple models like Logistic Regression combined with TF-IDF can perform well on structured text classification tasks.

## Interpretation
The model demonstrates that machine learning can effectively classify news articles based on their content. High accuracy indicates that different news categories contain distinct linguistic patterns that can be captured using simple NLP techniques.

## Limitations
- Short text samples
- Simplified binary classification
- No deep learning models used

## Future Work
- Use transformer models for improved accuracy
- Incorporate longer text and metadata
- Explore explainability techniques
