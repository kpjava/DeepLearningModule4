# NLP to Monitor Tweets for Natural Disasters

This project will use Natural Language Processing (NLP) and Recurrent Neural Networks (RNN) to monitor tweets to determine if a natural disaster is occurring. It can serve as an early warning system for the government or other organizations that can offer assistance to the people affected by the disaster.

The combination of an RNN with NLP, if successful, will monitor the real-time communication of users and classify their discussions as part of a natural disaster or not. I will explore a few architectures to determine the best technique to use (e.g., LSTM, GRU, etc.). This project is part of a pathway for a Master's degree from University of Colorado Boulder and also an active Kaggle contest (which compares the accuracy and validity of researches exploring the best neural networks to solve various problems).

The initial prerequisite for an RNN is to convert characters and words from users tweeting on X into mathematical representations, which is a common service offered by NLP. I will use spaCy, a python library to perform this step because it supports multiple languages, has pre-trained pipelines and supports TensorFlow and PyTorch. For the neural network aspect, I will use TensorFlow and Keras because of its simple interface.
