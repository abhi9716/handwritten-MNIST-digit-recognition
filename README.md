# Handwritten Digit Recognition Using OpenCV and Python

## Dataset used
For this project I used the MNIST dataset. It is freely available on the Internet.

## Requirements
1. Python 3
2. Sklearn
3. OpenCV 3
4. numpy
5. Jupyter-Notebook

## Training SVM model
1. <b>SVM_Classifier.ipynb</b> - This is a ipython notebook so you need jupyter-notebook installed to use this file. Use this file if you want to retrain the model.
2. <b>digits_cls1.pkl</b> - This is a saved SVM model file.

## Digit recognition using OpenCV
<b>dig_rec.ipynb</b> - This is a ipython notebook for recognising handwritten digit in images using OpenCV .This file is using trained SVM model <b>digits_cls1.pkl</b>.

## Real time single digit recognition using OpenCV
<b>dig_rec_vid.ipynb</b> - This is a ipython notebook for recognising single handwritten digit using webcam and OpenCV .This file is also using trained SVM model <b>digits_cls1.pkl</b>.

## Real time multi digit recognition using OpenCV
<b>multidig_rec_vid.ipynb</b> - This is a ipython notebook for recognising multi handwritten digit using webcam and OpenCV .This file is also using trained SVM model <b>digits_cls1.pkl</b>.

## How to use these projects
You can use these projects direct opening the perticular ipython notebook <b>dig_rec.ipynb</b> or <b>dig_rec_vid.ipynb</b> or <b>multidig_rec_vid.ipynb</b>.
