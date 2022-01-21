# Sentiment-Analysis-of-Amazone-Baby-Product-
 This project analyzes and develop a model to analyze and predict the sentiment given the costomer review for an amazon baby product. Turicreate is used for this work. The data set is highly biased towards the positive sentiment, so model is improved, by using only selected features for training the model.

## Exploring the Data
### Examining the most reviewed product

**Rating for the most reviewed product**
<img src="/visualization1.png?raw=true"/>

**Product rating analysis as general**
<img src="/visualization2.png?raw=true"/>

**Sentiment Analysis**

0 - 1 is for negative sentiment, and 1-2 is for positive sentiment
<img src="/visualization3.png?raw=true"/>


## Model Development

Developed model uses Logistic Regression algorithm. 
Performance metrics:
* 'f1_score': 0.9157860082304526,
* 'log_loss': 0.39622654670874996,
* 'precision': 0.8487520595594068,
* 'recall': 0.9943165570488991


For code: [Notebook](https://github.com/MuafiraThasni/Sentiment-Analysis-of-Amazone-Baby-Product-/blob/main/sentiment_analysis_baby_products.ipynb)
