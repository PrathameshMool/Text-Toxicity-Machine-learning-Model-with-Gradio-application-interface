# Text Toxicity Machine learning Model with Gradio application interface

Developing a machine learning model which analyze the the toxicity in comments/ texts and build an Gradio Application on the model


### link to Google Collab note book : https://colab.research.google.com/drive/1pDvs5inAGpQYmm3f_GSXjaINfrp_1x9j?usp=share_link

## Description

hello all the viewers who want to make a mchine learning model which identifies how toxic are the text/comments. and rate them according to the categories like threat, toxicity, insult, obscene language.

And build a Gradio Application to view the functioning of machine learning model

The process of building the application and presenting it


### Installing the dependencies like Tensdorflow, Tensorflow -gpu pandas sklearn
1.   Tensorflow - for building the machine learning models with help keras of
2.   Tensorflow-gpu - for harnessing the power of gpu for better computation power 
3.   Pandas - for building the data set from the given train CSV file


### Pre Processing the data
first we have to perform tokenization of data which is done by using Textvectorization from tensorflow.keras.layers

And prepare datapipeline to fed into the deep learning model

### Building a deep learning model
Creating a sequential model using tensorflow.keras.models importing Sequential Model

### Making Model prediction
### Evaluate the working of model
### Making a gradio for displaying the functionality of the machine learning model


## positive input 
![db_objects] (images/positive exaample.png)

## negative/toxic input 
![db_objects] (images/toxic text example.png)
