# Natural_Language_Processing

In this assignment we will use Natural Language processing to analyse news articles about two major cryptocurrencies, namely Bitcoin and Ethereum. 

We used the "newsapi" to fetch the news articles.  The results were saved in  json files, from which we created dataframes  to conduct various analyses.


A sentiment analysis was performed on both sets of articles, which returned the below results:

![sentiment_analysis](Images/sentiment_analysis.PNG)



 We will use these results to answer the following questions:

(1) Q: Which coin had the highest mean positive score?
A: The coin with the highest mean positive score was Bitcoin.

(2) Q: Which coin had the highest compound score?
A: The coin with the highest compound score was Ethereum.

(3)Q. Which coin had the highest positive score?
A: The coin with the highest positive score was Ethereum.


(4)Q. Which coin had the highest negative score?
A: The coin with the highest negative score was Ethereum.

We used NLTK and Python to tokenize the texts for each coin.  From this we were able to derive the following visualizations:

 (1) the top 10 words for each coin:

 ![top_words](Images/top_words.PNG)

(2) Word Clouds

Bitcoin Word Cloud


![bitcoin_wordcloud](Images/bitcoin_wordcloud.PNG)


Ethereum Word Cloud
![ethereum_wordcloud](Images/ethereum_wordcloud.PNG)
 
Additional analyses which can be found in the accompanying jupyter notebook, included bigrams and a list of the entities and labels related to both sets of articles.