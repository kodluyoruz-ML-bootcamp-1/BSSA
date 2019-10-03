## Team: BSSA

# Project Description
  ## Introduction
In this project, the state-of-art deep learning methods are used to to train a model that can drive a car in a simulator. For the use of simplicity and portability the udacity simulator is chosen https://github.com/udacity/self-driving-car .
  ## What it does? 
  > What are the inputs/outputs? How does it work?
The network takes three image inputs form the simulator, which are the front-view cameras that is placed on the car in the simulator. Other than this, network does not take any  other input. 
  ## Challenges
  > Difficulties encountered
At first, reinforcement learning methods were considered for this project. However, the limited time made us change this decision and we have decided on supervised learning instead.
 ## Achievements
 > Progress, accomplishments
The model can drive the car in both of the default roads in the udacity simulator. it can also get in the road if its outside of the road in most cases. 
  ## Future work
# Data 
 > Detailed data description
The dataset contains around 78k images that were taken from the simulator. The simulator also gives the steering angle, throttle and speed values corresponding to the time in which the corresponding image is taken  
 > Resource
# Folder Structure
 > Repository folder structure
The whole dataset that we have created in the following link https://drive.google.com/open?id=1DwzZTc3envrKN6nehlo2OHwV2P0OFMOI  
# Requirements
> Software, packages etc.
Tensorflow, Keras, Numpy, Pandas, matplotlib, sklearn, OpenCV, socketio, eventlet, Flask, PIL, base64
# How to Run
> How to run from the command line? How to reproduce the results?  How to test your system?
Firstly, the simulator executable file should be opened and autonomus mode should be chosen, then the following command should be run in the relevant folder.
```
python drive.py model-016.h5
```
# References
https://github.com/udacity/self-driving-car
End to End Learning for Self-Driving Cars - https://arxiv.org/pdf/1604.07316v1.pdf
