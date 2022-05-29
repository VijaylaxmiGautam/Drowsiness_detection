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

# Deployment
  Here's the link of the Source Code of our main file
  https://github.com/VijaylaxmiGautam/Drowsiness_detection/blob/main/Drowsiness_Detection.ipynb
 
 
# Video Demonstration
  Here's the link to the video demonstration of



# ADVANTAGES:
 It avoids the accidents while driving.
 Automatic monitoring system.
 It avoids potential human errors.
 
 # How to Run this Project Locally
 
 #Clone the given repository
 https://github.com/VijaylaxmiGautam/Drowsiness_detection.git
 
 #Run the command npm install in your terminal in the root directory of the project to install the various dependencies
 https://docs.npmjs.com/cli/v6/commands/npm-install
 
 
 
# Extension-:
 We can use live video capturing to feed photo frames to the model.if the Yawning and closing of eyes happens in short period of time,then the drowsiness level of the   perso is high.We can set bars as per experiments and data to see if the person is drowsy above the safe level.
 
# WORKING

Now initially we will remove the excess image part and will focus only on eyes and face.
We will use Casscade dataset for face detection.
Now we will convert the image to image array and reshape the array accordingly.
Then we will binarize the result values using a threshold using Label Binarization.
Using train test Split we will split the given data into training and testing data to make our model with test size as 30% and train size as 70%.
Then we will create the train and test data by using horizontal flip and rotation and will now fit this data to our model.


