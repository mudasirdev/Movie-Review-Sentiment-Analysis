**Movie Review Sentiment Analysis**

**Overview**

This project performs sentiment analysis on movie reviews to classify them as positive or negative. The analysis is conducted using Natural Language Processing (NLP) techniques and machine learning models.

**Features**

Preprocessing: Removes stopwords and cleans text data.

WordCloud Visualization: Generates word clouds for positive and negative reviews.

Machine Learning Model: Uses Logistic Regression for classification.

TF-IDF Vectorization: Converts text data into numerical form.

Model Evaluation: Uses confusion matrix for performance assessment.

Model Saving: Saves trained model and vectorizer using pickle.

**Dataset**

Source: IMDb Movie Reviews Dataset

Columns:

text: The review content

sentiment: Either positive (1) or negative (0)


**Dependencies**

Python (3.x)
NLTK
scikit-learn
WordCloud
Matplotlib
NumPy
Pandas
Streamlit (optional for UI)
