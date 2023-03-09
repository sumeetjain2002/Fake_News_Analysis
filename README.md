# Fake News Analysis
In this project, we aim to build a model that can classify news articles as either fake or real. We will be using the Naive Bayes model for classification.

# Prerequisites
Python 3.x

Pandas

Numpy

Scikit-learn

# Software

![images](https://user-images.githubusercontent.com/68370214/223942294-cab323fc-7156-4406-a25d-86c7215c3738.jpeg)


# Dataset
We will be using a publicly available dataset for fake news analysis. You can download the dataset from https://www.kaggle.com/datasets/hassanamin/textdb3?resource=download

# Steps
Import the necessary Python libraries and the dataset that we need for this task.

This dataset is very large and luckily it still has no missing values.

Load the dataset into a pandas DataFrame.

Use the title column as the feature we need to train a machine learning model and the label column as the values we want to predict.

Separate the dataset into training and testing sets, and then I’ll use the Multinomial Naive Bayes algorithm to train the fake news detection model.

Now let’s test this model. To test our trained model, I’ll first write down the title of any news item found on google news to see if our model predicts that the news is real or not
