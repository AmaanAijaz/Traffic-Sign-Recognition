# Traffic-Sign-Recognition

This project belongs to the domain of Machine Learning with the help of OpeCV.

The project involves training a model based o the dataset obtained on kaggle, (link:- https://www.kaggle.com/c/traffic-sign-recognition/overview ).


The data is coverted to a CSV file before the machine is trained on it.

For the purpose of training, a CNN was desiged.

More about CNN's can be read on https://www.analyticsvidhya.com/blog/2018/12/guide-convolutional-neural-network-cnn/

The CNN  was trained in batches of 32 as well as 64, but the 64 batch model was chosen as it provided a better accuracy. 


Then the model is saved by the name 'traffic_classifier-Batch64.h5'.

Currently, a GUI is in the works for the same model using Tkinter in Python
