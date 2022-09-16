#   Handwritten-Character-Recognition
#  Introduction
In this project, we have developed a deep learning model which predicts the character written/ drawn by a user. We have used Keras and Tensorflow.
#  Model Building and Training  
We have built the model using Keras and used its capability of creating a convolutional neural network to increase the accuracy of the model. We added various CNN layers to the model and tested it. The model sometimes gets confused between words and numbers which look similar( example: 'o' and 0, 'G' and 6.
#  Connecting the front end to the model and Deployment   
Using javascript and flask, we were able to capture the handwritten character and send it to the model which predicted the character and returned the label value, using which the flask was able to display the letter.
