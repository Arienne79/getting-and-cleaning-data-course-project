# Original Data

All datafiles have been downloaded from: https://d396qusza40orc.cloudfront.net/getdata%2Fprojectfiles%2FUCI%20HAR%20Dataset.zip

The following original datafiles have been loaden into R:

* x_train.txt
* y_train.txt
* subject_train.txt
* x_test.txt
* y_test.txt
* subject_test.txt
* features.txt
* activity_labels.txt

# Assiging column names
The following column names have been assigned to the data:
* features have been assigned to the x-data sets
* activityId has been assigned to the y-data sets
* subjectId has beem assigned to the subject-data sets
* activityId and activityType have been assigned to the activity label data set

# Merge all data
The train and test data sets have been merged

# Extract measurements on Mean and Standard deviation
A vector has been created for getting the mean and the standard deviation using grepl

# Set descriptive activity names
Activity names have been set

# Create a second tidy data set
The set tidyData.txt has been created
