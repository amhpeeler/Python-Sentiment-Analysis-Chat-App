# Python-Sentiment-Analysis-Chat-App
Uses Flask Sockets to create a live chat room application.

Uses a roBERTa Twitter trained model to detect sentiment in the conversation and update the background color based off of the sentiments score.

Red -> Negative sentiment score
Blue -> Neutral sentiment score
Green -> Positive sentiment score
Averages the last 15 texts for the background color.
