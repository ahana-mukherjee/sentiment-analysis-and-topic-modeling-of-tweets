# Sentiment Analysis and Topic Modeling of Tweets
Sentiment analysis and topic modeling of Russia-Ukraine war-related tweets

I performed sentiment analysis and topic modeling on the tweets for the ongoing conflict between Russia and Ukraine. I extracted approximately 5,000 tweets from Twitter containing the following hashtags:
1. '#UkraineUnderAttaсk'
2. '#UkraineRussiaWar'
3. '#RussiaUkraineConflict'
4. '#RussianUkrainianWar'
5. '#ukrainerussia'
6. '#WorldWar3'
7. '#RussiaVsUkraine'
8. '#StandWithRussia'
9. '#StandWithUkraine'

Using the generated data, I was able to determine the polarity and subjectivity of each tweet. 
Polarity is the intensity of an opinion, which may be positive or negative. Subjectivity is the degree to which an individual is personally invested in a topic, and it can be positive or negative or neutral.

I also performed Topic modeling on the data . Topic modeling is an unsupervised machine learning technique that can scan a collection of documents, detect word and phrase patterns within them, and automatically cluster word groups and similar expressions that best characterize a collection of documents.

I performed the modeling with the LDA (Latent Dirichlet allocation) model and then visualized the output with PylDavis. The model generated 10 different topics where each topic is a combination of keywords and each keyword contributes a certain weightage to the topic. 

Finally, I evaluated the model with topic coherence which measures the score of a single topic by measuring the degree of semantic similarity between high scoring words in the topic. These measurements help distinguish between topics that are semantically interpretable topics and topics that are artifacts of statistical inference.
