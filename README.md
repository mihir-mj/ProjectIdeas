# Final Year Project
American Sign Language Detection
Sign language is a type of language that uses manual
communication to convey meaningful messages to other
people. This includes simultaneous employing of hand
gestures, movement, orientation of the fingers, arms or
body, and facial expressions to convey a speaker's ideas.
American Sign Language is one of the popular sign language
used by most of deaf and dumb people to communicate with
each other. American Sign Language is also referred to as
ASL. A real-time sign language translator is required for
facilitating communication between the deaf community and
the general public. We propose a system called Dynamic
tool for American Sign Language (ASL) finger spelling
interpreter which can consistently classify the letters a-z. 
The dataset consists of a set of American Sign Language
videos. Our approach first converts the videos into frames
and then pre-processes the frames to convert them into
greyscale images. Then the Convolutional Neural Network
(CNN) classifier is used for building the classification model
which classifies the frames into 26 different classes
representing 26 English alphabets. Finally, the evaluation of
the classification model is carried out with test data
providing the output in the form of text or voice. The crossvalidation accuracy results of 98.66% is achieved from our
approach. 
# Dataset used 
https://www.kaggle.com/datamunge/sign-language-mnist
CSV Files - train.csv and test.csv
# Technologies used:
Keras
Tensorflow
