Financial Market News Sentiment Analysis
This project utilizes machine learning techniques to classify financial news articles or headlines into positive, negative, or neutral sentiments. By leveraging the Random Forest Classifier and Natural Language Processing (NLP), the analysis provides insights into market sentiment and its potential impact on financial trends.

Project Overview
Financial news plays a critical role in influencing market dynamics and investor behavior. This project involves:

- Preprocessing textual data from financial news articles.
- Applying sentiment classification using machine learning.
- Visualizing sentiment trends and analyzing their correlation with market data.
Objective
To classify financial news into sentiment categories and assess the relationship between news sentiment and market movements using the Random Forest Classifier.

Dataset
Financial News Data: Headlines or articles sourced from platforms like Yahoo Finance, Reuters, or publicly available datasets.
Sentiment labels are derived from manual annotations or financial lexicons (e.g., Loughran-McDonald sentiment dictionary).

Random Forest Classifier
The RandomForestClassifier was chosen for its ability to handle high-dimensional data and prevent overfitting through bagging. Key parameters tuned during model training include:

n_estimators: Number of trees in the forest.
max_depth: Maximum depth of the trees.
criterion: Function to measure the quality of splits (e.g., "gini" or "entropy").
