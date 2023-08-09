# Melanoma Detection Assignment

## Problem Statement:
> To build a CNN based model which can accurately detect melanoma. Melanoma is a type of cancer that can be deadly if not detected early. It accounts for 75% of skin cancer deaths. A solution that can evaluate images and alert dermatologists about the presence of melanoma has the potential to reduce a lot of manual effort needed in diagnosis.


## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)

## General Information
> The dataset consists of 2357 images of malignant and benign oncological diseases, which were formed from the International Skin Imaging Collaboration (ISIC). All images were sorted according to the classification taken with ISIC, and all subsets were divided into the same number of images, with the exception of melanomas and moles, whose images are slightly dominant.

The data set contains the following classes:

* Actinic keratosis
* Basal cell carcinoma
* Dermatofibroma
* Melanoma
* Nevus
* Pigmented benign keratosis
* Seborrheic keratosis
* Squamous cell carcinoma
* Vascular lesion

## Technologies Used
- Keras
- tensorflow
- pathlib
- matplotlib
- numpy
- pandas
- glob

## Conclusions
1.   The training accuracy is nearly ~90%.
2.   The validation accuracy is nearly ~83%.
3.   The Class rebalance has helped overcome overfit(Model1) as well as underfit(Model2). The model training and validation accuracy have improved with the help of class rebalance.
4.   Accuracy can still be improved by training the model for more epochs using the same CNN model
4.   Accuracy can also be improved by using more CNN and or Dense layers in the model.
