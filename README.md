# Vehicle-Tracking-System

In this project,we have developed a project in which we will track the vehicle based on the number plates.We have used YOU ONLY LOOK ONCE Version-8(YOLO V8) for this.
We have developed a model for extracting the information from images as well as videos.
Firstly,we will create a identify the number plate from video or image.We then plot a bounding box around a number plate.This bounding box will help us in extracting the information which is of use.

After the information is extracted,the text in this bounding box is identified.This text is returned and all the other components are preprocessed and blurred.This text is then extracted using EASYOCR which is a special librarry for extracting the text.

This text can then be used for performing different actions like tracking the vehicle.
The dataset which we have used for training the model so that it can understand the position of the number plate  is taken from RoboFlow.
