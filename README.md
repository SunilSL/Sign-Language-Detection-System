# Sign-Language-Detection-System
Realtime detection of hand signs through webcam.

Speech impaired people use hand signs and gestures to communicate. Normal people face difficulty in understanding their language.
Hence, there is a need of a system which recognizes the different signs, gestures and conveys the information to the normal people.
Thus we have developed an machine learning based sign language detection system which bridges the gap between physically challenged people and normal people.

* Technologies Used *
TensorFlow
OpenCv 
NUmPy 
TensorFlow Object Detection Api
SSD MobileNet ( Pre trained Model )

Training an entire convolutional network from scratch is time consuming and requires large datasets
This problem can be solved by using the advantage of transfer learning with a pre-trained model using the TensorFlow API.
Pre-trained models : People release their final ConvNet checkpoints for the benefit of others who can use the networks for fine-tuning. 
TensorFlow Zoo is one such place where people share their trained models/checkpoints The advantage of using a pre-trained model is that instead of building the model 
from scratch, a model trained for a similar problem can be used as a starting point for training the network.


Reference.
https://github.com/nicknochnack
