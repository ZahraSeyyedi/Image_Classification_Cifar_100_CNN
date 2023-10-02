# Image_Classification_Cifar_100_CNN


This project aims to classify images from the CIFAR-100 dataset using deep learning techniques. The CIFAR-100 dataset consists of 60000 32x32 colour images in 100 classes, with 600 images per class. The 100 classes in the CIFAR-100 are grouped into 20 superclasses. Each image comes with a "fine" label (the class to which it belongs) and a "coarse" label (the superclass to which it belongs). The goal is to classify each image into its corresponding class.
Data set : The CIFAR-100 dataset can be downloaded from the official website, or through the Tensorflow and Keras librares. It is split into a training set of 50,000 images and a test set of 10,000 images. Each image is a 32x32 pixel RGB image, with 3 color channels
Model : In this project, a convolutional neural network (CNN) is used to classify the images. The model consists of 6 convolutional layers. ReLU activation function is used for all the layers except the last layer, which uses a softmax function to produce the output probabilities for each class.

The model was trained on the training set for 200 epochs, with a batch size of 64 . The training process achieved an accuracy of 0.9028 with loss: 0.3633 on the test set.

result: in my opinion  the higher Dropout, the better accuracy
