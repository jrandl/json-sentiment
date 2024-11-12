# Requests, JSON, and basic NLP with spaCy

### Project Overview
This project demonstrates how to retrieve song lyrics using the `lyrics.ovh` API and analyze their sentiment using `spaCy` and `spaCyTextBlob`. The project retrieves lyrics, saves them in JSON files, and then performs sentiment analysis to determine the overall polarity of the lyrics. The polarity score indicates whether the lyrics have a positive, neutral, or negative sentiment.

## Question 1: Retrieve and Save Lyrics
Using the lyrics.ovh API, this project retrieves the lyrics of a specified song and saves them to a JSON file. This allows for offline access to the lyrics for subsequent tasks.

## Question 2: Sentiment Analysis on Lyrics
This step reads the JSON file containing song lyrics, extracts the lyrics, and performs sentiment analysis using spaCyTextBlob. It prints the polarity score, which ranges from -1.0 (very negative) to 1.0 (very positive).

## Question 3: Function to Retrieve and Save Multiple Songs
The music function takes an artist, song, and filename, retrieves lyrics from the API, and saves them in a JSON file. Four example songs are saved using this function.

## Question 4: Sentiment Analysis for Multiple Songs
This step loads each JSON file, performs sentiment analysis on the lyrics, and prints the polarity score along with the song title and artist.