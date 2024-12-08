# Sales analysis

## Dataset on Kaggle:

[Amazon Sales Dataset](https://www.kaggle.com/datasets/karkavelrajaj/amazon-sales-dataset)

## Description

This project applies advanced machine learning techniques to enhance e-commerce platforms by analyzing customer
behavior, predicting trends, and delivering personalized recommendations. Key components include sentiment analysis for
feedback evaluation, regression models for price forecasting, and a recommendation system using TF-IDF and cosine
similarity. These methods aim to improve customer engagement and support data-driven business decisions.

### Objectives:

1. **Data Preprocessing**

- Remove missing values, anomalies, and duplicates.
- Normalize and standardize variables for accurate analysis.

2. **Data Visualization**

- Create charts: histograms, box plots, scatter plots, and heatmaps.
- Analyze patterns, correlations, and trends in product categories, prices, ratings, and sales volumes.
- Identify product counts by category, top-5 discounted products, and review lengths.

3. **Comment Analysis**

- Determine sentiment (positive, negative, neutral) using text processing.
- Preprocess text: remove URLs, special symbols; tokenize and lemmatize.
- Visualize results with histograms.

4. **Price Prediction**

- Build a linear regression model to predict discounted prices using price, rating, and review count.
- Evaluate with MAE, MSE, RMSE, R² metrics.
- Visualize regression function and residuals distribution.

5. **Personalized Recommendations**

- `recommend_products`: Suggest 5 products based on TF-IDF cosine similarity of descriptions. Handle empty purchase
  history.
- `get_tfidf_matrix`: Compute and return the TF-IDF matrix for product descriptions.

## Technologies Used

- **Linear Regression**: Used for predicting discounted prices based on product attributes.
- **Neural Networks**: Used in comparison to Linear Regression.
- **NLP**: Preprocessing comments through tokenization, lemmatization, and sentiment
  analysis.
- **VADER**: Sentiment analysis tool designed specifically for social
  media, short texts, and product reviews.
- **TfidfVectorizer**: Converts product descriptions into TF-IDF vectors for similarity measurements.
- **Cosine Similarity**: Measures similarity between product descriptions for personalized recommendations.

## Conclusion

The study explores key machine learning techniques, encompassing text preprocessing, predictive modeling, and
personalized product recommendation generation. Sentiment analysis deciphers customer feedback, while regression models
and neural networks support product price forecasting. The recommendation system utilizes advanced methods like TF-IDF
and cosine similarity to deliver tailored offers. These approaches form the foundation for data processing workflows on
e-commerce platforms, enabling user behavior insights, accurate predictions, and personalized recommendations to enhance
customer interaction and drive business outcomes.
