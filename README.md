# Sentiment Analysis of Union Budget 2019

Social media has become an effective tool in any organisation’s public reception. People are more
engaged in the social life media nowadays thanks to availability of internet data. Online social media
analytics is a powerful tool to boost e-commerce, politics etc. In marketing field companies use it to
develop their strategies, to understand customers’ feelings towards products or brand, how people
respond to their campaigns or product launches and why consumers don’t buy some products.
Sentiment analysis also is used to monitor and analyse social phenomena, for the spotting of
potentially dangerous situations and determining the general mood of the blogosphere. In political
field, it is used to keep track of political view, to detect consistency and inconsistency between
statements and actions at the government level. It can be used to predict election results as well! In
this project we have a dataset of Union Budget 2019 of India that consists of tweets of public about
Budget and label that opinion is positive or negative.

__Disclaimer:__ Our sentiment analysis is purely based on collected data from tweets on the social
networking platform “Twitter”. The data is collected on an unbiased method. This analysis is solely
for educational purposes.

## Scope: 
In the following project, we use the sentiment140 dataset and uniondata dataset as training
and testing data respectively. Firstly we perform the Lexicon-Based Sentiment Analyser to find out
the count of positive and negative tweets from the union data.
Then comes the Machine Learning approach for sentiment analysis. In this technique, firstly the
dataset are splited in X_train and X_test dataset to conduct training with X_train and test the
performance with X_test. Following this, we clean up the test and training dataset and construct the
feature vector of the training dataset. Then, we implement the classifiers constructing individual
pipelines for each of them. Next, we train the dataset and store the performance metrics in a list.
Lastly we show the positive and negative sentiment count for each classifier and see which classifier
gives the best result.

Finally our aim is to answer our query, “The people like the new budget or not”.
