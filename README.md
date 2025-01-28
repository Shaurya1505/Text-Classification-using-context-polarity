This repository contains the implementation of a Context Polarity-based Text Classification algorithm. The project explores a novel approach to text classification by integrating semantic analysis into traditional models like Bag-of-Words (BOW) and Term Frequency-Inverse Document Frequency (TF-IDF). The proposed method leverages polarity scores for improved semantic understanding, offering flexibility across datasets of varying contexts. The algorithm is applied for two datasets with different contexts:
1) Sentiment Analysis Dataset:
   Contains 4000 hotel reviews labeled as positive or negative.
2) Spam-Ham Detection Dataset:
   Contains 5572 messages labeled as spam or ham.
Both datasets are sourced from Kaggle and preprocessed for polarity-based analysis.
The description for each file in the repository is as follows:

Hotel_data.csv: Dataset for sentiment analysis   
negativewords.txt: List of words with negative polarity   
positivewords.txt: List of words with positive polarity   
Senti_BOW&Polarity: Jupyter notebook for sentiment analysis using BOW and context polarity scores.   
Senti_BOW_TFIDF&Polarity: Jupyter notebook for sentiment analysis using BOW, TFIDF and context polarity scores.   
Senti_TFIDF&Polarity: Jupyter notebook for sentiment analysis using BOW and context polarity scores.   

spam.csv: Dataset for sentiment analysis   
spam.txt: List of words with spam polarity   
ham.txt: List of words with ham polarity   
spamham-BOW&Polarity: Jupyter notebook for spam-ham detection using BOW and context polarity scores.	  
spamham-BOW_TFIDF&Polarity: Jupyter notebook for spam-ham detection using BOW, TFIDF and context polarity scores.	  
spamham-TFIDF&Polarity: Jupyter notebook for spam-ham detection using BOW and context polarity scores.	  
