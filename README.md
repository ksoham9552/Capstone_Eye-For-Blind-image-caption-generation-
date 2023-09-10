# Project Name
> Image caption generation and voice description through CNN-RNN(encoder-decoder) to help blind people.


## Table of Contents
* General Info
	Steps followed as 
    1.Data Preprocessing: Processing image for inception V3 model, feature extraction and Caption processing for   
      encoder-decoder network
    2.Model Building: Encoder-Decoder-Attention model building
    3.Model Evaluation: Evaluation using Greedy search and BLEU score.
    4.Prediction on unseen data
    5.Caption to speech conversion

* Tools/Technology use:
	Python jyupitar notebook
	scikit-learn & statsmodel liabraries for regression fitting
        Tensorflow Keras library/methods
	NLTK tokenizer
	Pretrained Imagenet weights of Inception net V3 for feature generation
	RNN, GRU
* Conculsions:
	Successful model evaluation using greedy search and BLEU score.

## General Information
Capstone project aims to build,  a deep learning model which can explain the contents of an image in the form of text through caption generation with an encoder-decoder and attention mechanism on Flickr8K dataset. This kind of model is a use-case for blind people so that they can understand any image with the help of speech. The caption generated through a CNN-RNN model will be converted to speech using a text to speech library. First the features are extracted separately by using Inception V3 model then these features are passed to encoder. Afterwards Attention mechanism used and output of attention passed into decoder, where GRU is used to extract the caption based info.


## Acknowledgements
Give credit here.
- This project was inspired by UpGrad

## Contact
Created by [@ksoham9552] - feel free to contact me!

<!-- Optional -->
<!-- ## License -->
<!-- This project is open source and available under the [... License](). -->

<!-- You don't have to include all sections - just the one's relevant to your project -->