# Pneumonia-Detection-using-CNN

Convolutional Neural Network model to detect if chest xray provided is Normal or Affected with Pneumonia.

Dataset used -: https://www.kaggle.com/datasets/paultimothymooney/chest-xray-pneumonia

I further preprocessed to fit for training -: https://drive.google.com/file/d/1MwAhP9cQt-dEKviECKOnwk6VNbzGJ9-t/view?usp=share_link

You can train the model locally on your pc or on kaggle.

Kaggle is pretty good as it provides with GPU training and model training is etremely fast.

# 1. Setting up Environment for local training

Python version  3.10

Tensorflow version 2.10

Note -: Tensorflow is not supported on python 3.11 so be sure use proper interpreter.

If you have Nvidia GPU and want to use it for Training then install GPU version of tensorflow.

Tensorflow-gpu requires some prerequisites for proper working [check out this Tutorial](https://youtu.be/1Cs5NvLr6iM).

After Prerequisite is complete intall Tensorflow-gpu.

    pip install tensorflow-gpu

Verify Tensorflow GPU installation

    print("Num GPUs Available: ", len(tf.config.list_physical_devices('GPU')))
    
# Libraries

Pandas - `pip install pandas`

OpenCV - `pip install opencv-python`

Matplotlib - `pip install matplotlib`

Pickle, Time, os, Numpy, pathLib, random - Comes built-in wth Python
