# Brain Segmentation Using Keras and TensorFlow For Detecting Tumors

BRIEF INTRO: This repository contains code that uses UNET, Keras and Tensor flow to build, train and test a model that detects tumors in cancers patients. 




Directions:
1) you need to download the data set from ::
2) in the file "extract_patches.py", you need to specify the path of the data set
3) Pre-processing the data, training and testing can take a lot of time so expect that
4) Makefile is created for you so you can run:
$ make all 
and the whole program should compile and run (if you don't get any errors from the path specification :) )

Requirements
To run the code, you first need to install the following prerequisites:

Python 3.5 or above
numpy
keras
scipy
SimpleITK

I personally used Anaconda as there are a handful of dependencies used.





Credit: some of the work from https://github.com/Issam28/Brain-tumor-segmentation was used.