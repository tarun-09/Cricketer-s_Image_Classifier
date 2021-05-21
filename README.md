# Cricketer-s_Image_Classifier
Preinstalled modules required : Modules like tensorflow, opencv-python, seaborn, matplotlib, sklearn, pandas, numpy to be installed on your system.
These modules are needed to process their particular task.
In this project our first step is to import libraries then, read data set and split it and preprocess it. Then, define your model (Here, I used CNN with 4 covulational layer, 3 pooling layer, 3 dropout layer, 1 flattening layer and 2 Dense layers).
Then train your model on training data and validate it on validation data. Then, predict the accuracy on testing data.(In my case it is about 45.00% approx.).Then I plotted some curves of accuracy and loss then we predict the test dataset and compare it with actual results. Then we plotted a particular figure. Then we saw the confusion matrix. 
Now, Level 2 begins, We read the webcam and capture the face using "HAARCASCADE" and get that frame and predict it with the model we built in level 1 and display the output to he frame.

#Training data size : 440 images
#Validation data size : 49 images
#Testing data size : 87 images
#Accuracy Achieved : 45% approx.

I have uploaded two files:
1. For Google Colab because we have to run some additional scripts to access webcam in Colab.
2. For other platforms(I used Jupyter).
