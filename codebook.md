---
title: "Codebook"
author: "Nishant Sahni"
date: "January 27, 2016"
output: html_document
---
##Getting and Cleaning Data Course Project CodeBook

This file describes the variables, the data, and any transformations or work that I have performed to clean up the data.

    The site where the data was obtained:
    http://archive.ics.uci.edu/ml/datasets/Human+Activity+Recognition+Using+Smartphones
    The data for the project:
    https://d396qusza40orc.cloudfront.net/getdata%2Fprojectfiles%2FUCI%20HAR%20Dataset.zip
    The run_analysis.R script performs the following steps to clean the data:
    
    The run_analysis.R script performs the following steps to clean the data:
    
    1)  Read X_train.txt, y_train.txt and subject_train.txt and store them in their respectivce variables respectively.
    
    2) Read X_test.txt, y_test.txt and subject_test.txt and store them in testData, testLabel and store them in seperate variables.
    
    3) relabeling columns of the activity labels (read in previously)
    
    4) merging the y_train with the activity label
    
    5) giving  names from features to the X_train data frame
    
    
    6) Combining y_train, activity labels, X_train

    7) eliminating the first column from train2 to avoid error "duplicate column name"


  8)   selecting only the columns that contains means and std



9) Analysis of the 30% of the Volunteer select for generating the test data



10) merging the y_test with the activity label



11) giving names from features to the X_test data frame
colnames(X_test)<- features[,2]

12) Combining y_test, activity labels, X_test


13) eliminating the first column from train2 to avoid error "duplicate column name"


14) selecting only the columns that contains means and std



15)  Combining Train data with Test data


16) Summarizing the data
