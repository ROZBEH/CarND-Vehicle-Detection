# Vehicle Detection
[![Udacity - Self-Driving Car NanoDegree](https://s3.amazonaws.com/udacity-sdc/github/shield-carnd.svg)](http://www.udacity.com/drive)



Overview
---

In this project, our goal is to write a software pipeline to detect vehicles in a video. Before testing the pipeline on a video, we first try to make sure our vehicle detection classifier works on images file. After that, we get each frame of the video and pass it to the pipeline. Pipline will return the output video along with the bounding boxes around each vehicle.   
 

Pipeline
---
*The pipeline along with the corresponding python codes will be described here.*

*Note: I have not included the training data in my submission, because my github repository has limited space.*

<br>

I. Perform a Histogram of Oriented Gradients (HOG) feature extraction on a labeled training set of images and train a classifier Linear SVM classifier.

* We can also applied a color transform and append binned color features, as well as histograms of color, to the HOG feature vector.

* Features has been normalized and selection of training and testing set was random.

* Data set was divided into two sets for training(80%) and testing(20%).

* Some of the parameters that were used during training are listed in the following table.

<p align="center"><img src="examples/Table_Params.png" width = "350" alt="Combined Image" /> </p>

* Size of feature vector was 5772

* System was tested with different paramter combination that the current combination revealed the best testing accuracy. The following table shows the test accuracy for two cases.

<p align="center"><img src="examples/test_accu.png" width = "350" alt="Combined Image" /> </p>

</br>

<br>

II. 

</br>


<br>

III. 

</br>


<br>

IV. 

</br>


<br>

V. 

</br>


<br>

VI. 

</br>


<br>

VII. 

</br>