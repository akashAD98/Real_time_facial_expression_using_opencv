# Real_time_facial_expression_using_opencv



This project aims to recognize facial expression with CNN implemented by Keras.
It can  capture the real-time user's face through webcam steaming called by opencv.
OpenCV cropped the face it detects from the original frames and resize the cropped images to 48x48 grayscale image, then take them as
inputs of deep leanring model and it will predicts the expressions such as Happy,Sad,Neutral,Disgust,Angry etc


## Dataset
I used [fer2013](https://www.kaggle.com/c/challenges-in-representation-learning-facial-expression-recognition-challenge/data) dataset 

##  Requirements
pip install opencv-python==3.4.2.17.
pip install tensorflow==1.14.0.
pip install numpy.
pip install matplotlib.

