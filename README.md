# Handwritten-Digit-recognition
Task of CodeClause...!!!

Handwritten Digit Recognition using Convolutional Neural Networks in Python with Keras

MNIST dataset:
MNIST is a collection of handwritten digits from 0-9. Image of size 28 X 28

alt text

Code Requirements
python 3.x with following modules installed

numpy
seaborn
tensorflow
keras
opencv2
Description
This is a 5 layers Sequential Convolutional Neural Network for digits recognition trained on MNIST dataset. I choosed to build it with keras API (Tensorflow backend) which is very intuitive.

It achieved 98.51% of accuracy with this CNN trained on a GPU, which took me about a minute. If you dont have a GPU powered machine it might take a little longer, you can try reducing the epochs (steps) to reduce computation.

Execution
alt text

To run the code type,

python digit_recogniser.py

Tutorial
Note: This page is not complete. Sorry for delay.

Need help for this to be completed

For step-by-step tutorial please refer to wiki. It will take you through all the steps right from loading the data to recognising digits through live cam.

Update
For running on GPU enabled devices:
Please uncomment the following line from digit_recogniser.py (line no. 70) file:

tfback._get_available_gpus = _get_available_gpus
