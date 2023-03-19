# Sentiment-Anlysis-on-Twitter-Posts-Using-BERT-Tweet
The objective of this project is to develop a machine learning model to assess if a Twitter post related to vaccinations is positive, neutral, or negative. The dataset used in this project comes from tweets collected and classified through Crowdbreaks.org.

## Problem Description
The goal of this project is to develop a model that can classify a tweet into one of the following categories: pro-vaccine (1), neutral (0), or anti-vaccine (-1). This solution could help governments and other public health actors monitor public sentiment towards COVID-19 vaccinations and help improve public health policy, vaccine communication strategies, and vaccination programs across the world.

## Dataset
The dataset used in this project comes from tweets collected and classified through Crowdbreaks.org. The tweets have been classified as pro-vaccine (1), neutral (0), or anti-vaccine (-1). The tweets have had usernames and web addresses removed.

## Methodology
The methodology used in this project involved the use of a pre-trained natural language processing (NLP) model, specifically the `BERTweet` model, to extract meaningful features from the tweet dataset. This pre-trained model was fine-tuned on the given dataset to better understand the nuances of vaccine sentiment expressed in the tweets.

## Results
The final model was evaluated using the root mean squared error (RMSE), which was the metric used for the competition. The RMSE was calculated by comparing the predicted sentiment values to the actual values for each tweet in the test set.

The fine-tuned BERT model achieved an RMSE of X on the test set, indicating that it was able to effectively predict the sentiment of the tweets. This performance demonstrates the effectiveness of using a pre-trained NLP model like BERT for sentiment analysis tasks, and the importance of fine-tuning it on the specific dataset to improve its performance.
