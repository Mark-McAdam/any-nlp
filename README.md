
# any-nlp
This is a step by step guide how to approach any Natural Language Processing (NLP) problem using Keras, Tensorflow, and Glove Vectors.

This provided me a nice framework to do machine learning problems in the future. 

## Table of Contents
- [Description](#description)
- [Functionality](#functionality) 
- [Technology](#technology)
- [License](#license)

## Description 
For a competitive Kaggle challenge I used this notebook to put together and track my submissions. 

This was hosted at DS12 Whiskey Multiclass Classification problem 

(0, 1, 2) Classify the whiskey based on the the text description
- Excellent 0
- Good 1
- Bad 2

### Important directories 
- working (this is where the notebook is located, also where you need to download the glove vector text file to)
- input (this is the directory with the data)
- submission (this directory holds some of the submissions that I uploaded to the Kaggle Competition)
- first-attempt (this directory holds my first attempts at solving the problem)



## Functionality
In order to run the notebooks and follow along you will need to download the Glove Vectors, for this competition I used the glove.840B.300d.txt file this can be found on the github stanfordnlp page listed below. You will need to unzip the file in the same directory as the notebook in order to follow along. I did not include in this repository due to the large file size. 


https://github.com/stanfordnlp/GloVe

http://nlp.stanford.edu/data/wordvecs/glove.840B.300d.zip


## Technology
What are the technologies used?

- Natural Language Processing
- Keras preprocessing
- Keras LSTM, MaxPooling1d, 
- Stanford glove vectors
- Pandas
- Numpy
- Scikit-Learn train+test+split


## License
[![license](https://img.shields.io/github/license/DAVFoundation/captain-n3m0.svg?style=flat-square)](https://github.com/Mark-McAdam/any-nlp/blob/master/LICENSE)

Special thanks to Kaggle User Abhishek for the inspiration on how to apply NLP to various problems
https://www.kaggle.com/abhishek/approaching-almost-any-nlp-problem-on-kaggle
