# Fake-News-Detection
Implementation of a Fake news detection program using the Multinomial Naïve Bayes Classifier and Boolean Naïve Bayes Classifier with and without stop word removal

## Data
This repository requires the effects of stop-word filtering. This means removing common words from the train and test sets which is in the respective folders. The stopword list is in the "stopwords-ur.txt" file.

## Implementation 
The implemention contains the classifier training and testing code and evaluated them using Accuracy, Precision, Recall and F1 measures. Then, the model was evaluated again with the stop words removed. Finally, it is shown how this approach affects average accuracy (for the current given data set).