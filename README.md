# This repository holds the training and inference code for chaii question and answering (kaggle competition)
competition link: https://www.kaggle.com/c/chaii-hindi-and-tamil-question-answering

## Introduction
One of the task of this competition is mainly on extractive question and answering. We have been provided the context and the question and our task is to predict the "start" and "end" token of the answer span. While like may sound like a token classification task like other NLP task like NER. Extractive question and answering poses a challenge in the sense that the context lenght may be very long >3k tokens. In order to overcome this, pre and post processing must be done to break up the paragraphs (with overlap) and rejoin them back again.


## kaggle training scripts
training: https://www.kaggle.com/georgeteo89/chaii-hindi-tamil-training
inference: https://www.kaggle.com/georgeteo89/chaii-hindi-tamil-inference

## Huggingface spaces
Test out the model on huggingface spaces!
** do take note that inference time will be long 3-5mins as the model is over 2GB in size
https://huggingface.co/spaces/wolfrage89/chaii_spaces