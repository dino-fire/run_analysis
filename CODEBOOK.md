## Samsung Galaxy accelerometer application data analysis
This is a codebook file for the data acquisition and analysis of Samsung Galaxy accelerometer application data.

Raw data was obtained from https://d396qusza40orc.cloudfront.net/getdata%2Fprojectfiles%2FUCI%20HAR%20Dataset.zip

The data sets used in this process were...

  -  /train/X_train.txt
  -  /train/subject_train.txt
  -  /train/y_train.txt
  -  /test/X_test.txt
  -  /test/subject_test.txt
  -  /test/y_test.txt
  -  features.txt
  
The columns of main data, located in the 'X_train.txt' and 'Y-train.txt' files, have been renamed to descriptive labels using the values in
the 'features.txt' file.

All '/*train.txt' and '/*test.txt' data were combined into a single R data frame.

The 'subject' files and the 'X' files have been concatenated to append the proper subject to their corresponding accelerometer data.

The values in the activities column in the data set have been modified to descriptive names.

A new aggregated tidy dataset ('tidydata.txt') has been created.