# Data_Science_Project_Stock_Sentiment_Classification | Predicting market behavior from tweets

**Overview | Project Objective**

The goal of this project is to develop an NLP model capable of predicting market sentiment based on tweets. In summary, using NLP techniques, the model must be able to classify tweets received as input and predict, for each tweet, whether it describes a Bearish (0), Bullish (1), or Neutral (2) attitude.

The project was developed using python 3 and libraries such as NLTK and Scikit Learn.


**Corpora**

The data is divided in a file for training “train.csv”, and another file for testing “test.csv”:
  • Train (9543 lines): Presents the tweets (“text”) and the sentiment label (“label”). Each tweet can have one of the following labels: Bearish (0), Bullish (1), or Neutral (2) which it was divided in Train/Validation.
  • Test (299 lines): The structure of these dataset is the same as the train set, except that it does not contain the “label” column.


**Implementation**

- Data Exploration
- Corpus split
- Data Preprocessing
- Feature Engineering
- Classification models:
  - Logistic Regression
  - KNN
  - Naive-Bayes
  - Random Forest
  - Multilayer Perceotron - ANN  
- Model Valuation


