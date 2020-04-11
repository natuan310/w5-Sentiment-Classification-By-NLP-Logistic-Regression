# w5-Sentiment-Classification-By-NLP-Logistic-Regression
Movie Review's Sentiment Classification by Logistic Regression

## 1. Prepare the data
Train Data:  https://drive.google.com/open?id=1qfUh29q1BAnIz1AI5jviQZdbRFYM4FTK
Evaluate Data:  https://drive.google.com/open?id=1loD4WoqQlmV2uGufT1NslmHLoDtlwMk1

## 2. Clean our data
Get the 'review' and 'sentiment' columns for train data.
Drop duplicate found in data.
Data have no null values.

#### Stopwords
Use english stopwords from ntlk library.

#### Preprocessor
Use regular expression to remove HTML markup, non-word characters and move the emoticons to the end of each review.

#### Stemmer
Use PorterStemmer to normalize words in reviews.

#### Use Vectorizer to transfrom preprocess methods to vectorize method

#### Create Pipeline
Use Pipeline to apply preprocess methods to data then transfer data to our model

#### Test model with list of C parameter to find the max accuracy score

#### Apply best C parameter to model
