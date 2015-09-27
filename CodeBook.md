# Code Book
This code book is generated on 27 September 2015 for the assignment of Getting And Cleaning Data Course of Coursera Data Science course.

## Variable List
- subject: 1 to 30 each representing an ID of a participant in the study
- activity: Name of the activity
- featDomain: Time domain signal or frequency domain signal (Time or Freq)
- featAcceleration: Acceleration signal (Body or Gravity)
- featInstrument: Measuring instrument (Accelerometer or Gyroscope)
- featJerk: Jerk signal
- featMagnitude: Magnitude of the signals calculated using the Euclidean norm
- featVariable: Variable (Mean or SD)
- featAxis: 3-axial signals in the X, Y and Z directions (X, Y, or Z)
- count: Count of data points used to compute the average
- average: Average of each variable for each activity and each subject
 
## Study Design
The source data was collected from https://d396qusza40orc.cloudfront.net/getdata%2Fprojectfiles%2FUCI%20HAR%20Dataset.zip and unziped into the working directory. A folder named "UCI HAR Dataset" is created automatically.

R script called "run_analysis.R" that does the following is created.
- Step 1: Merge the training and the test sets to create one data set.
- Step 2: Extract only the measurements on the mean and standard deviation for each measurement
- Step 3: Use descriptive activity names to name the activities in the data set
- Step 4: Appropriately labels the data set with descriptive variable names
- Step 5: From the data set in step 4, creates a second, independent tidy data set with the average of each variable for each activity and each subject.

As a result "GettingAndCleaningData_Assignment.txt" file is generrated as the tidy dataset.
