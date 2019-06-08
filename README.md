# Arial Cactus Identification
Jupiter Notebooks for Arial Cactus Identification competition on Kaggle.

## Introduction
The goal of the [Aerial Cactus Identification competition](https://www.kaggle.com/c/aerial-cactus-identification) is to create an algorithm that can identify a specific type of cactus in aerial imagery to advance a system for autonomous surveillance of protected areas.

<br>In this competition, we are given a dataset with labeled 32 x 32 images, which contain arial photos of a columnar cactus. The task is to build an algorithm, which predicts whether there is a cactus on the image. This is a classification problem. Since we have a lot of data, deep learning models will suit well for this problem.

<br>In this analysis I used the code from this [Kaggle kernel](https://www.kaggle.com/atrisaxena/pytorch-simple-model-iscactus-classification).

## Data Exploration
* We are given 17500 (81.4%) images in train dataset and 4000 (18.6%) images in test dataset.
* The number of images with cactus in train dataset is 13136 (75.1%). The number of images without cactus in train dataset is 4364 (24.9%).
* Examples of images from the dataset:

## Approach
I used transfer learning and pretrained VGG-16 network to classify the images.

## Conclusion
I achieved 99.8% on validation dataset with 20 training epochs.
