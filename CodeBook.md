## About the source data
The source data are from the Human Activity Recognition Using Smartphones Data Set. A full description is available at the site where the data was obtained:
http://archive.ics.uci.edu/ml/datasets/Human+Activity+Recognition+Using+Smartphones
The data for the project: https://d396qusza40orc.cloudfront.net/getdata%2Fprojectfiles%2FUCI%20HAR%20Dataset.zip 

## R script
R script "run_analysis.R" performs the following steps:   
1. Reads in the files and merges the training and the test sets to a single data set.    
2. Extracts the measurements on the mean and standard deviation for each measurement     
3. Uses descriptive activity names to name the activities in the data set   
4. Labels the data set with descriptive variable names   
5. Creates a second, independent tidy data set with the average of each variable for each activity and each subject   

## About variables:   
`x_train`, `y_train`, `x_test`, `y_test`, `subject_train` and `subject_test` contain the data from the downloaded files.
`x_data`, `y_data` and `subject_data` merge the previous datasets for the analysis.
`features` contains the correct names for the `x_data` dataset
