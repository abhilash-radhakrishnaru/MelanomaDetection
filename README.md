# Melanoma Detection
Build a multiclass classification model using a custom convolutional neural network in TensorFlow


## Table of Contents
* [About the Domain](#About-the-Domain)
* [Problem Statement](#Problem-statement)
* [Input](#Input)
* [Conclusions](#Conclusions)   
* [Technologies Used](#technologies-used)
* [Acknowledgements](#acknowledgements)

<!-- You can include any other section that is pertinent to your problem -->

## About the Domain
Melanoma is the most serious type of skin cancer. It occurs when the pigment-producing cells that give colour to the skin become cancerous. Symptoms might include a new, unusual growth or a change in an existing mole. Melanomas can occur anywhere on the body. 

Though it is very fatal, it is curable in most cases if its detected in its early stages. Therefore having an automated, reliable, scalable system which can detect the disease by looking at the image is a life saver.

## Problem statement
Build a CNN based model which can accurately detect melanoma. Melanoma is a type of cancer that can be deadly if not detected early. It accounts for 75% of skin cancer deaths. A solution that can evaluate images and alert dermatologists about the presence of melanoma has the potential to reduce a lot of manual effort needed in diagnosis.

## Input
The input dataset consists of 2357 images of malignant and benign oncological diseases, which were formed from the International Skin Imaging Collaboration (ISIC). All images were sorted according to the classification taken with ISIC, and all subsets were divided into the same number of images, with the exception of melanomas and moles, whose images are slightly dominant.


The data set contains the following diseases:
- Actinic keratosis
- Basal cell carcinoma
- Dermatofibroma
- Melanoma
- Nevus
- Pigmented benign keratosis
- Seborrheic keratosis
- Squamous cell carcinoma
- Vascular lesion

## Conclusions
- With increase in epochs, the accuracy of both validation & training increases.
- With increase in epochs, the training & validation loss decreases
- The difference between the training & validation accuracy has decreased a lot compared to other two models.
- More images in the dataset, rebalancing & more epochs helps to improve the performance of the model


## Technologies Used
- python
- TensorFlow library
- pandas library
- matplotlib library
- numpy library

## Acknowledgements
Give credit here.
- This project was inspired by upGrad's CNN assignment