<img width="562" alt="Screenshot 2024-05-21 at 11 17 59 AM" src="https://github.com/astitwa1234/Sentiment-Analysis/assets/116952983/760731a0-45b1-4542-8c21-09c2b5704fb1">






# Sentiment-Analysis
The provided code implements a sentiment analysis project using Twitter data. Here's a summary of the project:

Data Preprocessing:

The Twitter data is loaded into a DataFrame.
Preprocessing steps include removing Twitter handles, special characters, numbers, and short words from the tweets. Additionally, stemming is performed to reduce words to their root forms.
Data Visualization:

Word clouds are generated to visualize the most frequent words in the entire dataset, as well as in positive and negative tweets separately.
Bar plots are created to display the top hashtags in positive and negative tweets.
Feature Extraction:

Bag-of-Words (BoW) representation is used for feature extraction, where the text data is converted into numerical vectors.
CountVectorizer is employed to convert the text data into a matrix of token counts.
Model Training and Evaluation:

The dataset is split into training and testing sets.
Logistic Regression model is trained on the training data.
Model performance is evaluated using F1 score and accuracy on the testing data.
The model's predictions are generated using probability scores, with a threshold of 0.3 for classifying tweets.
Performance Evaluation:

F1 score and accuracy are calculated to assess the model's performance in predicting sentiment labels (positive or negative) for the tweets.
Overall, the project involves preprocessing Twitter data, extracting features using BoW representation, training a Logistic Regression model, and evaluating its performance in sentiment analysis. The F1 score and accuracy metrics provide insights into the model's effectiveness in classifying tweets based on sentiment.







