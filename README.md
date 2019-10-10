
## THE INTERN TASK

The task at hand is to predict the ratings for a review from 1 to 5 given the train dataset. The dataset consists of different features such as :

- 1 App Version code
- 2 App Version Name
- 3 Review Text
- 4 Review Title
- 5 The Rating

## DATA REPRESENTATION TECHNIQUES

The main thing in NLP is how we represent the text. For word embedding in this notebook, I have used the BoW approach. I have implemented both the Count Vectorizer and the Tf-Idf vectorizer from the sklearn library.

## MODELING ALGORITHMS

Next major thing is the modeling algorithms used. Since the reprsentation is sparse (Count and Tfidf vectorizer) we can use the algortihms that are fast and scale well with the sparse data. So I have tried Logistic Regression,Xg-boosting and Multinomial Naive Bayes Models. ( The notebook finally concludes with making predictions on the test set.)

# Modeling

### Logistic Regression Model: with Tf-Idf:

Weghted F1 Score: 71

### Xg-Boosting Model: with Tf-Idf:

Weghted F1 Score: 71

### Xg-Boosting Model: with Countvectorizer:

Weghted F1 Score: 71

### Multinomial Naive Bayes Model: with Tf-Idf:

Weghted F1 Score: 71

### Multinomial Naive Bayes Model: with Countvectorizer:

Weghted F1 Score: 71
