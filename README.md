# Face_mask_detection Overview
*I used OpenCV(Open Source Computer Vision Library) to capture images with and without mask for data collection
* Convert Collected images data into array are saved in two files with_mask and without mask.
* Used viola jones face detection algorithm to detect face in picture
* Use Principal Component Analysis for dimensionality reduction of training and testing dataset
* Train Support Vector machine learning model to detect face weather wearing mask or not with 98% accuracy


# Resources used
**Python Version:** 3.9
**Packages:** pandas, numpy, sklearn, PCA, OpenCV
**Article:** https://brain-mentors.com/face-mask-detection-using-opencv-in-python/

# Data Collection and preparation
* Used openCV computer vesion library to capture face image without mask asd with mask. 
* save data into NPY file 
* merge both data set by row and did one hot encoding 0 for with mask and 1 for without mask
* use train_test_split method to split data into train and test dataset

# Model building
* According to our data use supervised classification machine learning algrith SVM.
* Train our model on train dataset and test our model on test data set and get 98% accuracy

# Test
* Write code for capture live face and detect weather person wearing mask or not.
