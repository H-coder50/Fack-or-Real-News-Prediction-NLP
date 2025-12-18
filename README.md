
# 🚀 **NLP Project: Fake vs Real News Prediction Model**
This is Natural Language Processing (NLP) project focused on building a Fake News vs Real News Prediction Model. This project demonstrates how Deep learning and NLP techniques can be used to analyze news text and identify misinformation.

### 🎯 Project Objective:

The main goal of this project is to:
-	Automatically classify news articles as Real or Fake
-	Apply complete NLP pipeline steps from raw text to prediction
-	Understand how text preprocessing and feature extraction impact model performance
### 🧠 Step-by-Step Approach:

##### 1️⃣ Data Collection
-	Used a labeled dataset containing real and fake news articles
-	Each record includes the news text and its label (Real / Fake)
##### 2️⃣ Data Cleaning & Preprocessing

To make the text suitable for machine learning:
-	Converted text to lowercase
-	Removed punctuation, numbers, and special characters
-	Removed stopwords (common words like is, the, and)
-	Applied tokenization
-	Performed lemmatization to reduce words to their base form
##### 3️⃣ Feature Extraction
-	Used TF-IDF (Term Frequency–Inverse Document Frequency)
-	Converted textual data into numerical vectors
-	Helped the model focus on important and meaningful words
##### 4️⃣ Model Building
-	Trained a Machine Learning classification model on TF-IDF features
-	Model learns patterns that differentiate fake news from real news
##### 5️⃣ Prediction Function
-	Created a custom predict_news() function
-	Takes raw news text as input
-	Applies the same preprocessing and TF-IDF transformation
-	Outputs prediction:
    -	✅ Real News
    -	❌ Fake News
##### 6️⃣ Model Evaluation
-	Tested the model on unseen news articles
-	Checked prediction probabilities and classification threshold
-	Analyzed cases where predictions were incorrect to improve logic
### 🔗 Conclusion:

This project strengthened my understanding of NLP pipelines, text classification, and Deep learning models. It’s a step forward in my journey toward Data Science and AI.

