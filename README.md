README FILE
This file describes how run_analysis.R script works.

    First, unzip the data from https://d396qusza40orc.cloudfront.net/getdata%2Fprojectfiles%2FUCI%20HAR%20Dataset.zip and rename the folder with "data".
    Make sure the folder "data" and the run_analysis.R script are both in the current working directory.
    Change the working directory in the setwd() command
    Second, use source("run_analysis.R") command in RStudio. 
    
The final output of when the script is run will be a tidy data set called run_analysis.text that will be saved to the working directory with the average of each variable for each activity and each subject.