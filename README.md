# Context

Amazon Fine Food Reviews dataset contains customer-written product reviews.

The project focuses on classifying reviews as Positive or Negative.

Reviews include text, summaries, ratings, and product details.

# Problem Statement

Build a model that accurately predicts the sentiment of a review.

Automatically identify whether customer feedback is positive or negative.

# Dataset Description
Input Features

Summary – Short review description

Text – Full review

Score – Rating (1–5)

ProfileName – Reviewer name

ProductId – Product identifier

Target Variable

Positive (1): 4–5 stars

Negative (0): 1–2 stars

Neutral (3-star reviews removed)

# Dataset Insights

Large review dataset with rich text information.

More positive reviews than negative.

Word clouds and length analysis provide sentiment patterns.

# Project Objective

Build sentiment classifiers using:

Machine Learning: Logistic Regression, Linear SVM, Naive Bayes

Deep Learning: BiLSTM, TextCNN

Compare accuracy, precision, recall, and F1-score.

Provide a user prediction option for any review.

# Workflow

Data cleaning (missing values, noise removal)

Combine Summary + Text into one Review field

TF-IDF vectorization for ML models

Tokenization & padding for DL models

Model training & evaluation with test data

Visualizations: bar plots, confusion matrices, word clouds

# Conclusion

The project successfully classifies customer reviews into positive or negative.

Deep Learning models show strong ability to understand semantic patterns.

Useful for businesses to analyze customer satisfaction at scale.
