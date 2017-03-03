# Sentiment-Analysis-on-Donald-Trump
Recently, the presidential candidate Donald Trump has become controversial. Particularly, associated with his provocative call to temporarily bar Muslims from entering the US, he has faced strong criticism.
Some of the many uses of social media analytics is sentiment analysis where we evaluate whether posts on a specific issue are positive or negative.
We can integrate R and Tableau for text data mining in social media analytics, machine learning, predictive modeling, etc., by taking advantage of the numerous R packages and compelling Tableau visualizations. 
Let’s mine tweets and analyze their sentiment using R. 
We will use Tableau to visualize our results. 
We will see spatial-temporal distribution of tweets, cities and states with top number of tweets and we will also map the sentiment of the tweets. This will help us to see in which areas his comments are accepted as positive and where they are perceived as negative. R packages used:
library(twitteR),library(ROAuth),require(RCurl),library(stringr),library(tm),library(ggmap),library(dplyr)
library(plyr),library(tm),library(wordcloud)

## Steps:
This is a Lexicon based sentiment analysis:

1. Get Twitter Authentication from https://dev.twitter.com/ account- library(twitteR) ,(ROauth)

2. Scrapping recent tweets from different cities using Lattitude & Longittude 

3. Getting addresses of tweets using google maps API(ggmaps package from R)

4. Creating a word cloud of the tweets to visualize the most common words in the tweets and have a general feeling of the tweets.

5. The most frequent words in the tweets are ‘muslim’, ‘muslims’, ‘ban’. This suggests that most tweets were on Trump’s recent idea of temporarily banning Muslims from entering the US.

6. Save data as csv & import it to Tableau.

7. Graphical representation for Various City & State.
