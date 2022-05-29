# Drowsiness_detection
 
# Features of Drowsiness detection
1.This project focuses on a drowsy detection Deep learning Model for prevention of road accidents because of this issue.
2.The objective of this  project is to build a drowsiness detection system that will detect that a person’s eyes are closed for a few seconds.
3.Our CNN model will have 5 layers containing 4 as relu as activation function and 1 softmax function and different parameters as per traditional model experiences.We have used relu as over sigmoid as Two additional major benefits of RELUs are sparsity and a reduced likelihood of vanishing gradient .

# About the Project
In this Python project, we will be using OpenCV for gathering the images dataset provided and feed them into a Deep Learning model which will classify whether the person’s eyes are ‘Open’ or ‘Closed’.
This model mainly uses image processing technology that focuses on the driver's face and eyes.
The model extracts the driver's face and predicts blinking in the eye area.
We use algorithms that track and analyze the driver's face and eyes to measure Perclos. 
If the flashing rate is high, the system will alert the driver with an audible sound.
The approach we will be using for this Python project is as follows :
- Take image as input from the data set provided.
- Detect the face in the image and create a Region of Interest (ROI).
– Detect the eyes from ROI and feed it to the classifier.
– Classifier will categorize whether eyes are open or closed.
– Calculate score to check whether the person is drowsy.



 
# Dataset
*Link to the Dataset:* https://drive.google.com/drive/folders/1qDPWOi0I8F1aiu3eg-mSLr2jP6a6EtoZ?usp=sharing

#powerpoint presentation
*link of presentation:*https://docs.google.com/presentation/d/106IQdvdQdGzG1WTiI7jaPyZaEanUcoOK/edit?usp=sharing&ouid=107699254071313598618&rtpof=true&sd=true

#output screenshots 
*link of folder*https://drive.google.com/drive/folders/11VQFDoc5qWzTtNyggVOUjGnbcGUxQ-L2

# Deployment
  Here's the link of the Source Code of our main file
  https://github.com/VijaylaxmiGautam/Drowsiness_detection/blob/main/Drowsiness_Detection.ipynb
 
 
# Video Demonstration
  Here's the link to the video demonstration of https://drive.google.com/file/d/1b6wJytupx8tuain5T0EeT_U92isYWb46/view?usp=sharing



# ADVANTAGES:
 It avoids the accidents while driving.
 Automatic monitoring system.
 It avoids potential human errors.
 
 # How to Run this Project Locally
 
 #Clone the given repository
 https://github.com/VijaylaxmiGautam/Drowsiness_detection.git
 
 #Run the command npm install in your terminal in the root directory of the project to install the various dependencies
 https://docs.npmjs.com/cli/v6/commands/npm-install
 
 
 
# WORKING

Now initially we will remove the excess image part and will focus only on eyes and face.
We will use Casscade dataset for face detection.
Now we will convert the image to image array and reshape the array accordingly.
Then we will binarize the result values using a threshold using Label Binarization.
Using train test Split we will split the given data into training and testing data to make our model with test size as 30% and train size as 70%.
Then we will create the train and test data by using horizontal flip and rotation and will now fit this data to our model.

We work in “Sprints” where each sprint lasts for a week or two, and focus on building the important features first and then improve the product to make it more potential.

Here are the sprints I had set for myself for the 4 week journey 😄
# WEEK 1 ( INITIAL DAYS )
 1.Learning more about APIs
 
 2.Researching about how image processing work ; what technologies / APIs / SDKs are used
 
 3.Deciding the Tech Stack and finding suitable resources

# WEEK 2 ( BUILD PHASE )
 1.Designing my model (using OpenCV,KERAS,tensorflow)
 
 2.Setting up the server and adding the functionality for eyes detection
 
 3.Styling and Testing

# WEEK 3 ( BUILD PHASE )
 Adding Basic libraries and dependencies
 1.from google.colab import drive
     drive.mount('/content/drive') 
     
 2.import pandas as pd
 
 3.import os
 
 4.import cv2
 
 5.from sklearn.preprocessing import LabelBinarizer 
 
 6.from sklearn.model_selection import train_test_split 
 
 7.from tensorflow.keras.layers import Input
 
 8.from tensorflow.keras.layers import Dense
 
 9.from tensorflow.keras.layers import Lambdas
 
 10.from tensorflow.keras.layers import Flatten
 
 11.from tensorflow.keras.layers import Convo2D
 
 12.from tensorflow.keras.layers import MaxPooling2D
 
 13.from tensorflow.keras.layers import Dropout
 
 14.from tensorflow.keras.models import Model
 
 15.from tensorflow.keras.models import Sequential
 
 16.from keras.preprocessing.image import ImageDataGenerator
 
 17.import tensorflow as tf
 
 18.import keras
 
 19.import matplotlib.pyplot as plt

# WEEK 4 ( X-FACTOR TIME )
 1.Examining and planning useful features for Drawsiness detection
 
 2.Converted the image to image array and reshape the array accordingly.
 
 3.Binarize the result values using a threshold using Label Binarization.
 
 4.Using train test Split,Splited the given data into training and testing data to make our model with test size as 30% and train size as 70%.
 
 5.Then created the train and test data by using horizontal flip and rotation and will now fit this data to our model.
 
 6.Making the product Responsive and Improving UI/UX
 
 7.Attaching dataset https://drive.google.com/drive/folders/1qDPWOi0I8F1aiu3eg-mSLr2jP6a6EtoZ?usp=sharing

 8.Working on making Video Demo & updating README.md
 
 
 # Extension-:
 We can use live video capturing to feed photo frames to the model.if the Yawning and closing of eyes happens in short period of time,then the drowsiness level of the   perso is high.We can set bars as per experiments and data to see if the person is drowsy above the safe level.
 


 

