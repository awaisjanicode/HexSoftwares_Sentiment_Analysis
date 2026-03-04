# HexSoftwares_Sentiment_Analysis
# HexSoftwares_Sentiment_Analysis

## 📌 Project Description

This project performs Sentiment Analysis on Amazon Alexa product reviews using Machine Learning techniques. 

The goal of this project is to classify customer reviews as **Positive** or **Negative** based on the emotional tone of the text. 

Sentiment Analysis is a Natural Language Processing (NLP) technique used to determine whether a piece of text expresses positive, negative, or neutral sentiment. It is widely used in analyzing customer feedback, social media posts, and product reviews to understand public opinion.

In this project, Amazon Alexa review data is used to train a Machine Learning model that can automatically predict the sentiment of new reviews.

---

## 🛠 Technologies Used

- Python
- Pandas
- NumPy
- NLTK (Natural Language Toolkit)
- Scikit-learn
- TF-IDF Vectorization
- Logistic Regression

---

## 📊 Dataset Used

- Amazon Alexa Reviews Dataset
- The dataset contains:
  - `verified_reviews` (Review text)
  - `feedback` (Sentiment label: 1 = Positive, 0 = Negative)

---

## ⚙ Project Workflow

The project follows the below steps:

1. **Data Loading**
   - Import dataset using Pandas
   - Select relevant columns (reviews and feedback)

2. **Data Preprocessing**
   - Convert text to lowercase
   - Remove punctuation and special characters
   - Remove stopwords
   - Clean and prepare text data

3. **Feature Extraction**
   - Convert text data into numerical format using TF-IDF Vectorizer

4. **Model Training**
   - Split dataset into training and testing sets
   - Train model using Logistic Regression

5. **Model Evaluation**
   - Calculate accuracy
   - Generate classification report

6. **Sentiment Prediction**
   - Create a function to predict sentiment of new reviews

---

## 📈 Model Performance

- Achieved high accuracy on test data.
- The model successfully classifies reviews into Positive and Negative sentiments.

---
## 🔍 Example Prediction

Input: "I love this Alexa device. It works perfectly!"
Output: Positive 😊

Input: "Worst product I have ever bought."
output:Negative 😡


---

## 🎯 Conclusion

This project demonstrates how Natural Language Processing and Machine Learning can be used to analyze customer feedback automatically. 

The trained model can help businesses understand customer opinions and improve their products and services based on sentiment analysis.

---

## 🚀 Internship Project

This project was completed as part of the Machine Learning Internship at HexSoftwres.
