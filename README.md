# sentiment_analysis_nlp
This project uses NLP to analyse sentiments after which comes training models DecisionTreeClassifer, LogisticRegressionClassifier and RandomForestClassifier with each following text processing technique: hashing TF IDF, hashing TF IDF with 2-bigrams and word2vec. The goal is to evaluate and discuss each combination of model and NLP technique.

We can see that metrics for all models are not good, but word2vec has an advantage among the text processing techniques (which is expected since it uses context to associate words with one another) and random forest has an advantage among the models (which is also expected since it's an ensemble algorithm).
