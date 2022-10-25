## This repository contains my code of emotion classification from twitter data

I did this project as part of my practice to learn NLTK and Text Classification

There are six emotion classes in the dataset.
- Anger
- Disgust
- Fear
- Joy
- Sadness
- Shame

Every class has 1096 Tweets. 

### Cleaning and Preprocessing

First I have done dataset cleaning and preprocessing. For cleaning, I have rmeoved unnecessary numbers, punctuation marks from the dataset.
Then I have removed the emoji/emoticons from the tweet and then the hastags.


## Training ML

for feature selection, I have used vectorization. I convert the tweets to same length vector and then create a Bi-LSTM model to classify the data.

Then in stage 2, I try to add convolutional NN for feature selection and check the result of the model.

And one the last stage, I train the model with pre-trained vectors (GLOVE)

