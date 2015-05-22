## Cleaning-Data-Course-Project
*First, all the similar data is merged using the rbind() function i.e. having the same number of columns and referring to the same entities.
*Then, only those columns with the mean and standard deviation measures are taken from the whole dataset. After extracting these columns, they are given the correct names, taken from features.txt.
*As activity data is addressed with values 1:6, we take the activity names and IDs from activity_labels.txt and they are substituted in the dataset.
*On the whole dataset, those columns with vague column names are corrected.
*From the a second, independent tidy data set with the average of each variable for each activity and each subject.

