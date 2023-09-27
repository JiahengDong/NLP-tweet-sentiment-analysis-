# NLP-tweet-sentiment-analysis-
Description: compare and analysis the performance of SVM model and Random Forest, classifying the tweets into positive, neutral and negative.
Technique used:
1. Text-preprocessing:
  1. Remove username and URL links
  2. Expand contractions and remove repeated letters 3. Remove stop words
  4. Lemmatize
  5. Remove retweets and repeated tweets
2. Data split:
  1. K-fold cross validation
  2. TFIDF
  3. Remove low variance features
  4. Select features with K best and chi-square
3. Models:
  1. Baseline: majority vote
  2. Select hyper-parameter: HalvingGridSearchCV
  3. 3. SVM model
  4. Random Forest
4. Evaluation:
  1. Accuracy, macro and weighted precision score, f1 score, recall score
  2. Confusion matrix
