# Mask-Detection-using-Kears
Mask Detection 

Detects if a person is wearing a mask or not through our webcam or any other device.Proper lighting condition are needed for the model to give better and accurate results.I implemented the entire model using CNNs.Having trained it for over 50epochs,I received an accuracy of 95.6% Tried to tune the hyperparameters using various methods.The best ones were used for the final training. Although its completely up to the users to use them in their own preferable way.

The link to the Mask dataset is here : https://github.com/prajnasb/observations/tree/master/experiements Since only about 1.5k images are given, try using augmentation for better results. The file webcam is where you load the pretrained model(mask_trained.h5).Its the file that acceses your webcam. Be sure to set the value of VideoCapture(x) to 1 or 0 as per your camera. I used my phone camera, hence I set it to 1.For webcam it should be set to 0.

Convolutional Neural Network (CNN) —

In deep learning, a convolutional neural network (CNN, or ConvNet) is a class of deep neural networks, most commonly applied to analyzing visual imagery. ... Convolutional networks were inspired by biological processes in that the connectivity pattern between neurons resembles the organization of the animal visual cortex.

![image](https://user-images.githubusercontent.com/68801296/89708419-95cf4f00-d994-11ea-8841-13765fcab844.png)
 
Keras :-

Keras is an open-source neural-network library written in Python. It is capable of running on top of TensorFlow, Microsoft Cognitive Toolkit, R, Theano, or PlaidML. Designed to enable fast experimentation with deep neural networks, it focuses on being user-friendly, modular, and extensible.

![image](https://user-images.githubusercontent.com/68801296/89708458-ff4f5d80-d994-11ea-98f4-d837e6d85293.png)
