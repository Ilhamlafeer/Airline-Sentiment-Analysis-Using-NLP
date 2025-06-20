✈️ Airline Sentiment Analysis Using NLP
This project performs sentiment analysis on airline tweets to classify them as **positive**, **neutral**, or **negative**. It applies classical Natural Language Processing (NLP) techniques and trains machine learning models to predict sentiment from tweet text.

📌 Features
- Text preprocessing: lowercasing, URL removal, tokenization, stopword removal, stemming
- Feature extraction using TF-IDF (top 3000 features)
- Model training with:
  - Multinomial Naive Bayes
  - Random Forest Classifier
- Performance evaluation using accuracy

📁 Dataset
- Dataset: `Tweets.csv`
- Columns used:
  - `text`: tweet content
  - `airline_sentiment`: sentiment label (target)
