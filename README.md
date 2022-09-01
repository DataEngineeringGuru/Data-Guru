# [Data Science Portfolio One Project overview](https://github.com/DataEngineeringGuru/Data-Science-Portfolio-One)

## Steps for setting up the website:
* Create a github account
* Make a new github repo and initialize the readme
* Go to settings 
* Go to GitHub pages and select master branch
* Select theme if you would like
* Go to the link at the top of the github pages secion 
* make any changes you would like to the markdown of the readme to get your content
* You now have a data science portfolio website!
* Note This is inspired fron a tutorial: How to Make a Data Science Portfolio by KenJee The Data Professor. 

# Ball Image Classifier(Source Ken Jee The Data Professor)
Data science project example using deep learning for image classification 

## Overview 
For this example project I built a ball classifier to identify balls from different sports. This could be useful for someone who is new to sports from a certain country. They could take a picture of a ball and an app could serve them some information about the history and rules of the game. This is the underlying model for building something with those capabilities. 

I was able to get the model to predict the sport of the ball with 94% accuracy after minimal tuning. For most of the cases this would meet the need of an end user of the app. To get these results I used transfer learning on a CNN trained on resnet34. This created time efficiencies and solid results. 

![alt text](https://github.com/PlayingNumbers/ball_image_classifier/blob/master/matrix_results.png)

## Notes
This notebook takes you through the process of creating an image classifer for various types of sports balls. It is the notebook that I use in the youtube video linked below. It is based of the [fastai lesson two notebook](https://github.com/fastai/course-v3/blob/master/nbs/dl1/lesson2-download.ipynb). 

## Config
I recommend using google colab for this project as it makes the gpu configuration far easier. In google colab make sure that you go to runtime -> change runtime type -> gpu. 

In colab, running the code should create the folder structure that you need. Drag and drop the photos located [here](https://drive.google.com/open?id=12cDnAIntmAYZ2lXXyeOa_GWdU926FYLU) into their respective folders. Technically you could skip the the folder creation and just drag and drop the data from the google drive into the colab file destination

## Data 
I used the following chrome extension to download the data from google images. [FatKun Batch Download Image](https://chrome.google.com/webstore/detail/fatkun-batch-download-ima/nnjjahlikiabnchcpehcpkdeckfgnohf?hl=en)
