# MBTI Personality Predictor

**Predicting Personality Types based on Social Media Posts**

## Overview

This project aims to predict Myers-Briggs Type Indicator (MBTI) personality types using machine learning techniques. The algorithm analyzes users' social media posts and classifies them into specific personality traits, including Introversion/Extroversion, Intuition/Sensing, Thinking/Feeling, and Judging/Perceiving.

## Key Features

- **Text Analysis:** Utilized Natural Language Toolkit (NLTK) for text analysis, implementing a bag-of-words model to extract meaningful features from social media posts.
- **Custom Dataset Preprocessing:** Engineered a comprehensive data preprocessing pipeline to handle missing values, remove stop words, reduce dimensioanlity and ensure data consistency.
- **Classifier Training:** Trained a Naive Bayes classifier for text classfication using NLTK's NaiveBayesClassifier.
- **Feature Representation:** Implemented Bag of Words model for efficient feature representation.
- **Testing and Evaluation:** Conducted rigorous testing and evaluation, achieving a high accuracy of 75% on unseen data which is quite good for basic Naive Bayes.

## Getting Started

1. **Clone the Repository:**
    ```bash
    git clone https://github.com/mayankzach/MBTI_Personality.git
    ```

2. **Install Dependencies:**
    ```bash
    pip install -r requirements.txt
    ```

3. **Run the Predictor:**
    ```bash
    python MBTI_Prediction.py
    ```


## Acknowledgments

- [NLTK Documentation](https://www.nltk.org/)
- [Scikit-Learn Documentation](https://scikit-learn.org/)
- [Bag-of-words-model](https://scikit-learn.org/](https://machinelearningmastery.com/gentle-introduction-bag-words-model/)https://machinelearningmastery.com/gentle-introduction-bag-words-model/)
