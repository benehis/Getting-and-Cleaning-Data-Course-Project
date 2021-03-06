Getting-and-Cleaning-Data-Course-Project
========================================
The data linked to from the course website represent data collected from the accelerometers from the Samsung Galaxy S smartphone. A full description is available at the site where the data was obtained: 
http://archive.ics.uci.edu/ml/datasets/Human+Activity+Recognition+Using+Smartphones 

Here are the data for the project: https://d396qusza40orc.cloudfront.net/getdata%2Fprojectfiles%2FUCI%20HAR%20Dataset.zip 

An R script was created called run_analysis.R that does the following: Merges the training and the test sets to create one data set; Extracts only the measurements on the mean and standard deviation for each measurement; Uses descriptive activity names to name the activities in the data set; Appropriately labels the data set with descriptive variable names; and Creates a second, independent tidy data set with the average of each variable for each activity and each subject. 

The tidy dataset created is a text file which can also be opened with an excel programm for clarity.

The zip file containing both training and test dataset was manually downloaded into a directory called RCourse in my computer. Thereafter, the run_analysis R script was applied to the raw dataset to tramsform it to the tidy dataset.
