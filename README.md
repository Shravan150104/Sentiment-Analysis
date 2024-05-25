# Twitter-Sentiment-Analysis
Twitter sentiment analysis analyzes the sentiment or emotion of tweets. It uses natural language processing and machine learning algorithms to classify tweets automatically as positive or negative based on their content. It can be done for individual tweets or a larger dataset related to a particular topic or event.

We aim to analyze Twitter sentiment analysis Dataset using machine learning algorithms, the sentiment of tweets provided from the Sentiment140 dataset by developing a machine learning pipeline involving the use of three classifiers (Logistic Regression, Bernoulli Naive Bayes, and SVM)along with using Term Frequency- Inverse Document Frequency (TF-IDF). The performance of these classifiers is then evaluated using accuracy and F1 Scores.

Upon evaluating all the models, we can conclude the following details i.e.

Accuracy: As far as the accuracy of the model is concerned, Logistic Regression(0.83) performs better than SVM(0.82), which in turn performs better than Bernoulli Naive Bayes(0.80 ).

F1-score: 
The F1 Scores for class 0 and class 1 are :
For class 0: Bernoulli Naive Bayes(accuracy = 0.80) < SVM (accuracy    =0.81) < Logistic Regression (accuracy = 0.83)
For class 1: Bernoulli Naive Bayes (accuracy = 0.80) < SVM (accuracy = 0.82) < Logistic Regression (accuracy = 0.83)

AUC Score: 
Bernoulli Naive Bayes(AUC = 0.80) < SVM (AUC=0.82) < Logistic Regression (AUC= 0.83)

We, therefore, conclude that the Logistic Regression is the best model for the above-given dataset.
