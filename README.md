# Getting-and-Cleaning-Data---Course-Project
This is the code book describing how the script works and the variables for Coursera "Getting and Cleaning Data".

1) Read the tables into R
2) Merges the training and the test sets to create one data set
3) Convert merged into data.table. Load "data.table" package.
4) Subset merged_dt to extract only the measurements on the mean and standard deviation for each measurement
5) Name all the mean and std measurements. I only include the entries that include mean() and std() at the end
6) Extract the activity names and store it for merging in the next step
7) Melt the data set where the ActivityName and Subject become ID and all the mean and standard deviation measurements become variables. Load "reshape2" package.
8) Dcast mergedActivityMelt to get the average of each variable for each activity and each subject.


