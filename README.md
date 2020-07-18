# covid19-tweets-sentiment-analysis
Sentiment analysis of COVID-19 tweets dataset (Part of IBM hack challenge)

CoViD-19 is a deadly and highly contagious disease. It has left the world's largest economies in peril. Worldwide governments are implementing 'lockdowns'. People are staying in homes everywhere. It is natural behaviour to feel secluded and bored while having minimal social contact. The only means of any contact is through 'Social media' . People from all around the world are voicing their concerns and sharing their daily routine etc.  But where there are people, there are bound to be disputes.

In problem statement, we would look at twitter and analyse the tweets having covid19 tag. We would the ntry to understand sentiment behind these tweets.  

To provide a solution for this, we would require the help of Natural language processing or NLTK for processing and understanding the tweets and figure out sentiment behind it and understand the emotions and purpose of the person writing the tweet.

We would proceed in the following way :  
1.The sentence is tokenized, so it is represented by a list of strings
2.We separately split subjective and objective instances to keep a balanced uniform class distribution in both train and test sets.
3.We use simple unigram word features, handling negation
4.We apply features to obtain a feature-value representation of our datasets and finally train the model

The novelty in this approach is that it maps the tweet in various different metrics for a deeper understanding of the sentiment.

Social Impact : The tweets can be analysed for provocative sentences or keywords and rightful action can be taken on the tweet before it is published on public domain.

Technology stack :
Python3
NLTK or other NLP API's like IBM Watson etc
Keras/Tensorflow
Sublime editor
