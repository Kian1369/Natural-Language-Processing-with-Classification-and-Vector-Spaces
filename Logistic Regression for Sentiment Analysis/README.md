# Logistic Regression for Sentiment Analysis

![Tweet](Tweet.png)

## Project Overview
This project was the last section of the NLP specialization with classification and vector spaces authorized by DeepLearning.AI and offered through Coursera. The main goal is to implement logistic regression for sentiment analysis on tweets. The model predicts whether a tweet has a positive or negative sentiment.

## Project Details
### Key Features
- **Feature Extraction:** Extract features for logistic regression from text.
- **Model Implementation:** Implement logistic regression from scratch.
- **Application:** Apply logistic regression to a sentiment analysis task.
- **Testing:** Test the logistic regression model.
- **Error Analysis:** Perform error analysis to improve the model.

### Data
We use a dataset of tweets, specifically:
- **Positive Tweets:** 5,000 tweets with positive sentiment.
- **Negative Tweets:** 5,000 tweets with negative sentiment.

### Steps
1. **Import Libraries and Data:**
   - NLTK library for natural language processing tasks.
   - Download Twitter samples and stopwords.
2. **Data Preparation:**
   - Split data into training and test sets (80% training, 20% test).
   - Create frequency dictionaries to count word occurrences.
3. **Preprocessing:**
   - Tokenize tweets, remove stopwords, and apply stemming.
4. **Model Implementation:**
   - Implement logistic regression using the sigmoid function.
   - Calculate cost function and gradients.
   - Train the model using gradient descent.
5. **Evaluation:**
   - Test the model on the test set.
   - Analyze errors to understand model performance.

### Results
The model is expected to achieve high accuracy in classifying the sentiment of tweets.
