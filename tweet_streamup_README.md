# Tweepy_sentimentanalysis
Our goal in this project is to use tweepy to collect data from Twitter and conduct sentiment analysis on the tweets to gauge public opinion on a specific topic.
This Python code performs real-time sentiment analysis on incoming Twitter data by processing the tweets streamed through a socket connection. The sentiment analysis is based on the polarity and subjectivity of the words present in the tweets, which are determined using the TextBlob library.

Installation

To use the code, the TextBlob library needs to be installed by running "pip install textblob" in the command prompt or terminal.
Usage

Run the Python script on a server or local machine with an active internet connection.
The code reads the tweets from a socket connection on port 5555. Make sure that the socket connection is properly set up and tweets are being streamed through it.
The output of the sentiment analysis is continuously updated and stored in memory as a stream, which can be accessed using queryName("tweetstream").
The code triggers every 2 seconds by default and performs sentiment analysis on the new incoming tweets during each trigger.
License

This code is open-source and can be used and modified for personal and commercial purposes with no restrictions.
