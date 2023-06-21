# Binary_classifier
Transfer Learning with MobileNet. Using transfer learning on a pre-trained CNN to build an Alpaca/Not Alpaca classifier!
A pre-trained model, mobileNetV2 that has already been pre-trained on a imageNet (over 14 million images and 1000 classes.) was used to customize a model for binary classification purpose. The weights of the pre-trained model helped to solve the calssification problem in the new dataset. This follows an implementation of data augmentation and preprocessing using Tensorflow Sequential API. Adapting the pretrained model to new data and training a classifier using the Tensorflow Functional API and MobileNet. Finally, Fine-tuning the classifier's final layers to improve accuracy

# Objectives
* Building a Binary Classifier by transFer learning with MobileNet
* Data augmentation with the Tensorflow Sequential API
* Adapting the pretrained model to new data with the Functional API and MobileNetV2
* Fine-tuning the classifier's final layers to capture high-level details near the end of the network, improving and
  boosting the model's accuracy

  # Reference
  Part of my assignment of Course 4 (Convolutional Neural Networks, week 2) in the Deep Learning 
  Specialization course!, deeplearning.ai. Some of this code are part of the assignment from deeplearning.ai
