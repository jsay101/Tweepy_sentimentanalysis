# Tweepy_sentimentanalysis
Our goal in this project is to use tweepy to collect data from Twitter and conduct sentiment analysis on the tweets to gauge public opinion on a specific topic.
This code is a Python script that uses the Tweepy library to stream real-time tweets that match a given filter criteria and send the text data to a local socket. The script can be executed from a Python environment such as Jupyter Notebook or an IDE.

To use the script, you need to install Tweepy using pip. Once installed, you need to provide the following Twitter API credentials:

consumer_key
consumer_secret
access_token
access_token_secret
After you have provided the credentials, you can specify the filter criteria that you want to use to receive the tweets. In this script, the filter criteria is set to "Fifa".

When you run the script, it will create a listening socket on your local machine and start streaming real-time tweets that match the filter criteria. The script sends the text data of the tweets to the listening socket in real-time.

You can modify the filter criteria to match any keyword you like. Note that the code only streams English tweets. If you want to stream tweets in other languages, you can modify the filter to include the language code.

The script is designed to receive the streaming data from the socket on the client side. The received data can be used for further analysis or storage.
