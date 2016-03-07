# CleaningData
Steps
======
Download and extract the files in your working directory.
Place the r script in the working directory.
Run the R script run_analysis.r
It produces tidy.txt, run_analysis.md, run_analysis.html


# Program Description step by step

# It is considered the required files are downloaded and extracted under the folder 
# named "UCI HAR Dataset" in the working directory

##################################################################### 
# setting project path

##################################################################### 
#Reading - files.

##################################################################### 
# Merges the training and the test sets to create one data set.
# Concatenate the data tables. 
# Merge columns. 
# Set key.

#####################################################################
# Extracts only the measurements on the mean and standard deviation for each measurement.
# Seperating variables in dt are measurements for the mean and standard deviation
# Subset only measurements for the mean and standard deviation.
# Convert the column numbers to a vector of variable names matching columns in dt

# Subset these variables using variable names

#####################################################################
#Uses descriptive activity names to name the activities in the data set
#Reading activity_labels.txt file - later - used to add descriptive names to the activities.

#####################################################################
#Appropriately labels the data set with descriptive variable names.

# Merge activity labels.
# Add activityName as a key.
# Melt the data table to reshape it from a short and wide format to a tall and narrow format.
# Merge activity name.

# Creating factor class

#Seperate features from featureName

## Features with 2 categories

# Possible combinations feature Vs factor class variables

#####################################################################
# From the data set in step 4, creates a second, independent tidy data set with the average of each variable for each activity and each subject.


# Creating codebook
