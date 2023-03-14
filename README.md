# Computer Vision Rock Paper Scissors

Rock-Paper-Scissors is a game in which each player simultaneously shows one of three hand signals representing rock, paper, or scissors. Rock beats scissors. Scissors beats paper. Paper beats rock. The player who shows the first option that beats the other player's option wins. This is an implementation of an interactive Rock-Paper-Scissors game, in which the user can play with the computer using the camera.

This project makes use of the following tools.

## Teachable Machine


[Teachable Machine](https://teachablemachine.withgoogle.com/) is a web-based educational tool which can be used to train neural networks and so create machine learning models based on images, sounds and poses.

## Conda and Miniconda

Conda is an open source package management system. It can be used to find and install packages in any language. It is also an enviroment manager, which enables you to set up multiple environments to run different versions of Python.
  
Miniconda is a minimal installer for conda which only includes Conda, Python, their package dependencies and some commonly used packages.

## OpenCV(Open Source Computer Vision Library)
Computer vision is a field of AI which derives information from digital images, videos and other visual inputs. OpenCV is an open-source library that provides access to hundreds of computer vision algorithms.

## Milestone 1
- The GitHub repository is setup

## Milestone 2: Create the Computer Vision System
The computer vision system is This is also known as a model. This particular model detects whether the user is showing Rock, Paper or Scissors to the camera.

The model is created using the Teachable Machine image project. A standard image model is created with four different classes: Rock, Paper, Scissors, Nothing.

For each pose in front of the camera, the camera angle, pose and scale is varied to get a large image data set, and as such, more accurate model results. For this project, around 500 images for each pose were generated.

After the classes are generated, the neural network is trained. For this project the default training parameters were used:

Epochs: 50
- The number of times the learning algorithm will work through the training dataset

Batch size: 16
-  The number of samples at a time that will be propagated through the network 

Learning rate: 0.001
- Controls how the model converges

The model is downloaded resulting in two files, keras_model.h5 and labels.txt.

## Milestone 3: Create the Computer Vision System
