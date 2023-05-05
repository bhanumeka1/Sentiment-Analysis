This project involved sentiment analysis on data scraped from Twitter using Python and natural language processing techniques. The analysis focused on tweets related to NCSU university using specific hashtags.

The project will involve the following steps:

Web Scraping: It uses the Tweepy library and the Twitter API to collect tweets containing relevant hashtags like #ncsu, #ncstate, #gopack, #thinkanddo, and #1pack1goal.

Preprocessing: The raw text data is preprocessed to remove unnecessary characters like punctuations and stop words.

Feature Extraction: Features are extracted from the preprocessed text using the bag-of-words approach and TF-IDF. This creates a matrix of word counts for each tweet and uses TF-IDF to weigh the importance of each word.

Model Training: A sequential neural network model is implemented with embedding layer, LSTM, CNN, GRU, and dense output layers. The model is trained using binary cross-entropy loss and the Adam optimizer.

Model Evaluation: The model's performance is evaluated on the testing set using metrics like accuracy, precision, recall, and F1-score.
