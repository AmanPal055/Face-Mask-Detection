# Face-Mask-Detection
Face Mask Detection system using OpenCV and Tensorflow/Keras

#Introduction
Face mask detection has a range of applications from capturing the movement of the face to facial recognition which at first requires the face to be detected with very good precision. Face detection is more relevant today as it is not only used on images, but also in video applications like real-time surveillance and face detection in videos.


#Process of Face Mask Detection with Machine Learning
Step 1: Extract face data for training.
Step 2: Train the classifier to classify faces in mask or labels without a mask.
Step 3: Detect faces while testing data using SSD face detector.
Step 4: Using the trained classifier, classify the detected faces.

In the third step of the above process, you have to think about what is the SSD face detector? Well, the SSD is a Single Shot Multibox Detector. This is a technique used to detect objects in images using a single deep neural network.
It is used for the detection of objects in an image. Using a basic architecture of the VGG-16 architecture, the SSD can outperform other object detectors such as YOLO and Faster R-CNN in terms of speed and accuracy.
