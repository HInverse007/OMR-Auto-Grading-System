# OMR-Auto-Grading-System

The major goal of our project is to find the result of the candidate by matching their response with the ideal responses of the questions provided.

Team Members : 
* Salay Jain 
* Harsh Sharma

# Working:

Download the zip file of the repo or clone the repo from the link : https://github.com/salay-jain/OMR-Auto-Grading-System . Or you can use the command git clone https://github.com/salay-jain/OMR-Auto-Grading-System

Some of the python3 libraries required are : numpy, matplotlib, PIL, imutils and argparse. Make sure to run these commands witout any error
*  import numpy 
*  import matplotlib.pyplot 
* from PIL import Image 
* import cv2 
* import imutils 
* import argparse 

Run the command: python3 main.py --inp1 Path to template image --inp2 Path to ideal answerkey --inp3 Path to the to be tested OMR sheet. For default you can use : `python3 main.py --inp1 ./Dataset/i1.jpeg --inp2 ./Dataset/i2.jpeg --inp3 ./Dataset/test0.jpeg`

The program will give outputs as : 
* Points Matching for the Ideal answer sheet
* Points Matching for the Students answer sheet
* Checked OMR - Right Answers by Green & Wrong answers by Red and unresponded are left blank
* Total result

To see our other works and observations refer to the python notebook (.ipynb) file where our algoritm is analysed for many diiferet types of input and output.

We have created our own dataset and it can be downloaded from the link : https://github.com/salay-jain/OMR-Auto-Grading-System/tree/master/Dataset .So to analyse our code on new images just specify the path as argument to the main.py file.While in our .ipynb file we have use the structuring like all our images are kept in the Dataset folder and we can acces them from there.

Hope we are able to solve your problem of OMR grading and made the solution to this problem easier and cheap that can be used by small instituions/coaching centers etc. easily with efficient outputs.
