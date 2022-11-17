# About this project:

This project is my 1st try on transformer. It examined a Kaggle competition tweet datasets. Tweets are commonly used for sentiment analysis, but the goal of this competition was to predict words/ phrases that
actually led to the sentiment labeling (positive, negative, or neutral):
- My motivation was the application of transformer, which is used primarily in the fields of natural language processing (NLP). 
- For prediction of the words/ phrases, I framed the task as a question-answering task. The output was a set of 3 predictions for each tweet, and ultimately the 
submission file with the best prediction extracted. 
- I got to apply tokenization, lemmatization, bag-of-words, etc., followed by the training & prediction using a Hugging Face model based on BERT architecture. 
- A challenge I faced was the extent of data cleaning required & the determination of useful arguments for training of the transformer model, which is 
computationally expensive. 

A future improvement is to devise more specific regular expressions for different use cases in data cleaning for performance improvement & efficiency.

## Visualizations:
<img src="https://github.com/nouzen-dev/ML_NLP/blob/main/4_Prediction of Text Extraction from Tweets for Sentiment Labeling/images/jaccard.JPG" alt="alt text" width="500"/>
<img src="https://github.com/nouzen-dev/ML_NLP/blob/main/4_Prediction of Text Extraction from Tweets for Sentiment Labeling/images/sentiment.JPG" alt="alt text" width="500"/> 
<img src="https://github.com/nouzen-dev/ML_NLP/blob/main/4_Prediction of Text Extraction from Tweets for Sentiment Labeling/images/sentiment_2.JPG" alt="alt text" width="500"/>
<img src="https://github.com/nouzen-dev/ML_NLP/blob/main/4_Prediction of Text Extraction from Tweets for Sentiment Labeling/images/sentiment_3.JPG" alt="alt text" width="500"/>
<img src="https://github.com/nouzen-dev/ML_NLP/blob/main/4_Prediction of Text Extraction from Tweets for Sentiment Labeling/images/venn.JPG" alt="alt text" width="500"/>
<img src="https://github.com/nouzen-dev/ML_NLP/blob/main/4_Prediction of Text Extraction from Tweets for Sentiment Labeling/images/unique.JPG" alt="alt text" width="500"/>
<img src="https://github.com/nouzen-dev/ML_NLP/blob/main/4_Prediction of Text Extraction from Tweets for Sentiment Labeling/images/simpletransfomers_Q%26A_data_format.JPG" alt="alt text" width="500"/>

![Python](https://img.shields.io/badge/python-3670A0?style=for-the-badge&logo=python&logoColor=ffdd54)
![NumPy](https://img.shields.io/badge/numpy-%23013243.svg?style=for-the-badge&logo=numpy&logoColor=white)
![Pandas](https://img.shields.io/badge/pandas-%23150458.svg?style=for-the-badge&logo=pandas&logoColor=white)
![scikit-learn](https://img.shields.io/badge/scikit--learn-%23F7931E.svg?style=for-the-badge&logo=scikit-learn&logoColor=white)
![PyTorch](https://img.shields.io/badge/PyTorch-%23EE4C2C.svg?style=for-the-badge&logo=PyTorch&logoColor=white)
