# Twitter Sentiment Analysis 

## Overview  
This project focuses on classifying tweets into **positive** or **negative** sentiment using Natural Language Processing (NLP) and Deep Learning.  

Neutral sentiments were intentionally removed to reduce complexity and make the model more focused.  
An **LSTM (Long Short-Term Memory)** network was trained on preprocessed tweets to capture sequential dependencies in text and deliver accurate sentiment predictions.  

## What’s Inside  
- **Tweet Preprocessing**:  
  - Cleaning tweets (removing links, hashtags, special characters).  
  - Tokenization into meaningful words.  
  - Removing stopwords.  
  - Filtering out neutral sentiments (only positive and negative kept).  

- **Model Architecture**:  
  - LSTM-based classifier designed for sequential text data.  
  - Hyperparameter tuning for performance optimization.  

- **Evaluation Metrics**:  
  - Accuracy: ~79% achieved on test data.  
  - Precision, Recall, and F1-score tracked for balanced evaluation.  
  - Comparative analysis against baseline models.  

## Why It Matters  
Tweets reflect real-time public opinion. By classifying sentiment into positive or negative, this project shows how NLP can be applied to:  
- Monitor brand reputation.  
- Track customer feedback.  
- Analyze public reaction to events, policies, or products.  

## Results  
- Accuracy: **79%** with tuned LSTM model.  
- Performance improved significantly compared to baseline sentiment classifiers.  
- Limitations observed due to imbalanced dataset. 
