# Persian Fake News Detection

This repository contains my dissertation which is Persian fake news detection. To achieve this model, I created a dataset that you can find more information about it from [here](https://github.com/Zarharan/PersianStanceDetection).

## Dataset
I am using the first Persian dataset which can be used for a number of NLP tasks in the context of fact-checking. Although this dataset can be used for fact-checking and summarization, the focus of this work is on stance classification as a stepping stone for fake news detection in Persian language.

## The Model

I have used our stance detection system as a pre-processing step. As a result, the head-claim stance and the article-claim stance are two important features in addition to other features like the credibility of the news source to determine the veracity of claims. Finally, after extracting stances for each claim and news article pair, we have combined the stances result and the rest of the features. Then, this feature is assigned to 3 dense neural network layers with 300 neurons each. At the end, there is a dense layer with a softmax activation function to specify the proper class (true, false, or unknown). The overall architecture is shown in the following Figure.

![My proposed model in order to develop fake news detection](https://github.com/Zarharan/PersianFakeNewsDetection/blob/main/Files/Model.png)

**This book will be updated during the various stages of the dissertation.**

