# OIBSIP_DataAnalytics-_task4-L1
This project focuses on sentiment analysis of text data to classify opinions as positive, negative, or neutral. Using Natural Language Processing (NLP) and machine learning techniques, the project analyzes customer feedback and social media text to understand public opinion and trends.
# Sentiment Analysis

## Objective
The objective of this project is to analyze text data and classify sentiments into positive, negative, or neutral categories. This helps understand customer opinions, feedback, and social media trends using Natural Language Processing techniques.

## Dataset
Dataset 1 Link: Twitter_Data.csv.zip

Dataset 2 Link: (Add dataset link)

The dataset contains text data such as customer reviews, feedback, or social media posts used for sentiment classification.

## Tools & Technologies
- Python
- Pandas
- NumPy
- Natural Language Processing (NLP)
- Scikit-learn
- Matplotlib
- VS Code

## Steps Performed
1. Collected text datasets containing reviews or comments.
2. Cleaned and preprocessed text data by removing stopwords, punctuation, and irrelevant characters.
3. Converted text data into numerical features using techniques such as TF-IDF or Bag of Words.
4. Applied machine learning algorithms for sentiment classification.
5. Evaluated model performance.
6. Visualized sentiment distribution using charts.

## Code (Example)

```python
from sklearn.feature_extraction.text import TfidfVectorizer
from sklearn.naive_bayes import MultinomialNB

vectorizer = TfidfVectorizer()
X = vectorizer.fit_transform(text_data)

model = MultinomialNB()
model.fit(X, labels)

Key Insights

Sentiment analysis helps understand public opinion and customer feedback.

NLP techniques allow machines to interpret human language.

Sentiment classification can support better marketing and business strategies.

Outcome

The project successfully classifies text data into different sentiment categories and provides insights into public opinion and customer feedback.

Author

Ayesha Asna
