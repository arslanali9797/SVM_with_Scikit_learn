# SVM_with_Scikit_learn
## In this project we are going to indentify the personality through machine learning where we use support vector machine with scikit learn. the dataset is alredy provide inside the scikit learn librery.The project is also cover the  deployment phase in local host .This project is going to  predict the personality with image.

# Dependencies
import matplotlib.pyplot as plt

from matplotlib import image


from PIL import Image


import numpy as np


import cv2 


# Introduction 

This project is based on image classification,where different personalities images are used to train the model. After that we will identify the image with their name.To achive our purpose we are going to implement the Scikit librery with SVM(support vector Machine )
we know that SVMs are a powerful class of supervised learning algorithms for classification and regression problems. In the context of classification, SVMs can be viewed as maximum margin linear classifiers.We will also give you an oppertunity to deploy this over the localhost with the help of Flask plartform .No need to wory about data set the file will automatically download the datased from scikit learn librery .

### Now the time to follow the procedure to run the project

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




