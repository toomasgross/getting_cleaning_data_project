Project work for Getting and Cleaning Data course 
-------------------------------------------------

Summary of the project
----------------------

The goal of the project was to prepare tidy data set based on data available at  https://d396qusza40orc.cloudfront.net/getdata%2Fprojectfiles%2FUCI%20HAR%20Dataset.zip  
This is data collected from the accelerometers from the Samsung Galaxy S smartphone.


Specific aims of the project 
----------------------------

The task was to create one R script called run_analysis.R that does the following: 

1. Merges the training and the test sets to create one data set.
2. Extracts only the measurements on the mean and standard deviation for each measurement. 
3. Uses descriptive activity names to name the activities in the data set
4. Appropriately labels the data set with descriptive variable names. 
5. From the data set in step 4, creates a second, independent tidy data set with the average of each variable for each activity and each subject.


Information about this repository 
---------------------------------

Apart from the current file, this repository contains 3 other files:

run_analysis.R - This script performs the 5 tasks described above
tidy_data_set.txt - a text file that contains tidied final output when running the run_analysis.R script
CodeBook.md - the file contains the definitions of each column in tidy_data_set.txt file
