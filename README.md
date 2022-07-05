# My-Work
## Project Title
Smile Detection - 
Determining if a subject in a photo is smiling or not.
 
## Demo link:
Access my site at [me.google.com](https://google.com)
 
## Table of Content:
 
- [Business Understanding](#business-understanding)
- [Data Understanding](#data-understanding)
- [Setup](#setup)
- [Technologies](#technologies)
- [Approach](#approach)
- [Screenshots of Visualizations/Results](#screenshots-of-visualizations/results)
- [Status](#status)
- [Credits](#credits)
- [License](#license)
 
## Business Understanding 
Being able to detect human emotions based on images is a valuable resource for many organizations looking to improve customer service. Chatbots could use emotion detection technology to better support their clients. In order to utilize this type of artificial intelligence, training machine learning models to determine the difference between a sad or angry facial expression is paramount. In this project, I made use of a dataset that contained over 28,000 examples. 

## Data Understanding

## Setup
- download or clone the repository
- load Anaconda
- open Jupyter Notebook
 
## Technologies
- Anaconda
- Jupyter Notebooks
- Python libraries: cv2, time, matplotlib, IPython, numpy, scipy, sklearn, OpenCV
  
## Approach
This lab is presented with a binary classification task. There are two classes: one containing all the pictures where there is a smiling face and the other group containing a face that is not smiling. The goal of the model is to assign a data point to one of the two classes: smiling and not smiling. They come from the datasets that can be found in 
https://www.kaggle.com/datasets/debanga/facial-expression-recognition-challenge.  In this lab, the original target variables were replaced with binary labels, a smiling face or a not smiling face.
 
The dataset has been divided into a training and a test set. 75% of the data is in the training set and 25% is in the test set. It is good practice to do this to evaluate the model performance, and to avoid having a super complicated model that fits the training data perfectly but does not generalize, known as overfitting.
 
An offline pipeline is implemented to see how the model works on two test images. Then, the same steps will be embedded in an online pipeline, so that the smile detector will work in real time, acquiring the images from the camera.

## Screenshots of Visualizations/Results
 
[screenshot](https://github.com/username/My-Work/blob/main/Screenshot.PNG)
 
## Status
Smile Detection is still in progress. `Version 2` will be out soon.
 
## Credits
List of contributors:
- [John Doe](johndoe.com)
- [Cisco Networking Academy](link-goes-here.com)
 
## License
 
MIT license [@ MyName] (author.com)


