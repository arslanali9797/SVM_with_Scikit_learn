# SVM_with_Scikit_learn
## Introduction
This project is based on image classification, where different personality’s images are used to train the mode. This model is trained on 8 different personalities. It will analysis the image (inclusive of 8 persons) and identifies the name. To achieve our purpose we are going to use Scikit library with SVM (support vector Machine) we know that SVMs are a powerful class of supervised learning algorithms for classification. We will also give you an opportunity to deploy this over the local host with the help of Flask platform .No need to worry about dataset the file will automatically download the dataset from scikit learn library

## Problem Statement
In this project we are going to identify the personality through machine learning where we use support vector machine with scikit learn. the dataset is already provide inside the scikit learn library .The project is also cover the deployment phase in local host .This project is going to predict the personality with image.


## Methodology 
In this project we are using Scikit library with SVM (support vector Machine). Support Vector Machines is one of the most popular and widely used supervised machine learning algorithms. Our model is going to trained with some other components. 
Like we use PCA (principal components analysis) .PCA-based data selection and image feature extraction for SVM classification. PCA allow reduce the features without losing the data.


With PCA we use pipeline, used to sequentially apply a list of transforms and a final estimator. The purpose of the pipeline is to assemble several steps that can be cross-validated together while setting different parameters. 


In Last GridSearchCV is use to provide the best hyperplane .it will give the optimal parameter which best fit our model .after applying the all-important concepts our model is now trained.


## Conclusion
We use SVM module with rbf (Radial basis function) kernel .and we use with PCA to reduce to features that is 150 features, then we use GridSearchCV gives the optimal parameter(c,gama) for better performance. In last we accrue the model accuracy with 81%.


### Now the time to follow the procedure to run the project


# Dependencies
import matplotlib.pyplot as plt

from matplotlib import image


from PIL import Image


import numpy as np


import cv2 



## step 1 
first your have to download all the necessary librery to successfully run the file .All libreries are mentioned above.

## step 2
now clone or download  the project at your work place .

## step 3 ( Download Dataset)
This is mandatory step, make sure that the ipynb file run successfully .if ipynb file run successful then the dataset will be download automatically for that we use scikit learn.Scikit learn contain some dataset so we use that dataset one of them . File contain codes and description and comments, if you want to know more detail about code go for the links
 https://drive.google.com/drive/folders/1QtA74AKimFurP23LuF_Mc8J2ECBOVej1?usp=sharing

## step 4
After successfully running the file ,we train our model with images .we use Scikit learn along svm to identify the name by given input images. Our model is trained and it will give you the name of personality of that image you have given .

## step 5 (Now you can test any image in our model)
This is testing phase although the model test is done in the file but we also test our model through external image (images that not include in dataset). you can load any images from 8 selected personalizes then test it and  get the result   
This project is under development phase, we are unable to deploy the project on local web services, that can be deploy in future. 

## For more details please visit
 ### Video (sharable link)
https://drive.google.com/drive/folders/1QtA74AKimFurP23LuF_Mc8J2ECBOVej1?usp=sharing
### Database 
We use scikit learn library, so scikit learn library contain some dataset, we use one of them having named “fetch_lfw_people” that consist of  multiple celebrity images.But due to less number of images we chose 8 celebirities having good no of images . There is no worry about dataset just few line of code will download the dataset easily. 




