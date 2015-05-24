#Getting and Cleaning Data: Course Project
==========================================
##Introduction
----------------
####This repository contains my project work for the Coursera course "Getting and Cleaning data"

##About Raw Data
----------------
####The feature data found in x_test.txt and the activity lables data found in y_test.txt file.The subject_test.txt file. 
####The same is for training data  

##About the script and the tidy dataset
-------------------------------------
####Created a script called run_analysis.R which merge the test and training sets together.
####Prerequisites for this script:

####1. The UCI HAR Dataset must be extracted 
####2. The UCI HAR Dataset must be preset in a directory called "UCI HAR Dataset"

####After merging testing and training, the labels are added and only columns with mean and standard deviation are kept.

####Lastly, the script creates a tidy data set with the means of all the columns per test subject and per activity.
####This tidy dataset written into a tab-delimited file called HAR-tidy.txt, which can also be found in this repository.

####About the Code Book
-------------------
####The CodeBook.md file explains the transformations performed and the resulting data and variables.
