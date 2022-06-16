# NLP_Comedians_Transcripts

In this project I have performed Natural Language Processing on Transcripts of various comedians.

First I have used beautiful soup for web scraping. I have collected transcripts of 7 different comedians. Then performed data cleaning on the collected transcripts like removing puntuation, digits, and also performed lemmatization to convert a word to its root form. Then I have created document-term matrix after removing the stop words.

Next I have found some general conclusions from the cleaned transcripts like using word cloud to find which words are most commonly used by a comedian and compared their vocabulary and talking speed. I also compared how much a comedian makes use of bad words and how much does a comedian speaks about family and friends.

Then I have used TextBlob to perform sentiment analysis by comparing polarity (How much positive or negative a comedian speaks) and subjectivity (about personal opinion and emotions) of the selected comedians. Polarity of different comedians is also checked after splitting their cleaned transcripts into multiple parts.

At last, I have performed text generation i.e., generating text from the cleaned transcript of a comedian using Markov's chain i.e., probability of each event depends only on the previous event.
