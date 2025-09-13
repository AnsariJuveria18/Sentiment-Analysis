📊 Sentiment Analysis Project

This project implements a Sentiment Analysis Pipeline that classifies text into positive, negative, or neutral sentiments.
It combines multiple NLP techniques including tokenization, stopword removal, lemmatization, POS tagging, and sentiment scoring.

---

 🚀 Features

• Text preprocessing: cleaning, tokenization, stopword removal, stemming & lemmatization
• POS tagging and Named Entity Recognition (NER)
• Sentiment classification using:

  • NLTK’s SentimentIntensityAnalyzer
  • TextBlob polarity & subjectivity
  • SpaCy for linguistic analysis
• Evaluation with confusion matrix and classification report

---

 🛠 Tech Stack / Libraries

• re, string → Regex & punctuation handling
• NLTK → stopwords, tokenization, stemming, lemmatization, POS tagging, SentimentIntensityAnalyzer
• TextBlob → polarity & subjectivity sentiment scores
• SpaCy → advanced NLP processing & named entity recognition
• Pandas → data handling
• Scikit-learn** → classification\_report, confusion\_matrix
• typing (List, Dict, Union) → type hinting for cleaner functions

---

 🔎 Workflow

• Data Preprocessing

  • Remove punctuation & special characters using regex
  • Tokenize text into words/sentences
  • Remove stopwords
  • Apply stemming & lemmatization
• NLP Processing

  • POS tagging
  • Named Entity Recognition (NER)
• Sentiment Scoring

  • Vader Sentiment (NLTK)
  • TextBlob sentiment analysis
• Evaluation

  • Confusion Matrix
  • Classification Report (precision, recall, f1-score)

---

 🎯 Use Cases

• Social media sentiment monitoring (Twitter, Reddit, YouTube comments)
• Product review analysis (Amazon, Flipkart)
• Customer feedback insights
• Movie review classification

