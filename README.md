# Lyrics Generator with LSTM

Notebook for generating lyrics using LSTM network. The dataset contains all the songs recorded by Bob Dylan. 

## Stages:
1. EDA
    - Summary statistics on dataset: distribution of no. of characters, words, sentences in collection
    - Histograms & wordclouds
2. Preprocessing
    - Create corpus of all words from lyrics
    - Cleaning: remove special characters, convert to lowercase
    - Create mapping of unique chars to indices
    - Create features and targets (categorical)
3. Model
    - Train LSTM model, one character at a time
    - Visualize learning and loss
4. Generation
    - Generate lyrics from seed phrase, one character at a time, using model predictions
