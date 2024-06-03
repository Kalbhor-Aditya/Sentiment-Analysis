# Sentiment Analysis 

This project focuses on the task of sentiment analysis using two different techniques: 

* VADER
  
* RoBERTa, a pretrained model 

## Techniques Used

1. **VADER (Valence Aware Dictionary and sEntiment Reasoner)**: VADER is particularly good at understanding sentiment in social media text, like tweets and online comments. It works by looking at a list of words with positive or negative connotations, and then considering things like capitalization and punctuation to get a more nuanced understanding of the feeling behind the text.

2. **RoBERTa**: This is a transformer-based model that was trained using the RoBERTa training approach. It's a variant of BERT and is highly effective for various NLP tasks.

## Dataset

The dataset used in this project is the Amazon Reviews dataset. The total length of the data is 568,454 reviews. However, due to the time it would take to train the models, only a subset of 10,000 reviews was used for this project.

## Applications of Sentiment Analysis
1] Customer Feedback: Sentiment analysis can be used to automatically analyze customer reviews and feedback about products or services. This can help businesses understand how their customers feel and make improvements accordingly.

2] Social Media Monitoring: Companies can use sentiment analysis to monitor social media platforms for public opinion about their brand and products. It can also be used to detect trends in sentiment over time.

3] Product Analytics: Companies can use sentiment analysis to gather insights from user reviews about specific product features, helping them to prioritize areas for improvement or development.

## Note

The models might take a long time to train if the entire dataset is used. Therefore, it's recommended to use a subset of the data for initial experiments.

## Future Work

Future work could involve using the entire dataset for training. Additionally, other pre-trained models could also be explored for this task.

