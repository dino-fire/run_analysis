The R script (run_analysis.R) in this repository is a self-contained program to download, manipulate, summarize, and ultimately output a tidy data 
file as a requiremetn of the Coursera Getting and Cleaning Data Course Project.

The data is accelerometer information from a test among 30 subjects using the Samsung Galaxy smartphone app which measures physical
activity.  

The data for this project may be found here...

https://d396qusza40orc.cloudfront.net/getdata%2Fprojectfiles%2FUCI%20HAR%20Dataset.zip

...and can also be access by running the R script itself.

The run_analysis.R script is completely documented for easy use.  In summary, the R script...
 
   - downloads and unzips the appropriate data file into a working directory
   - converts the raw data into R data frame objects
   - merges the train and test data into a single files for analysis
   - appends the subject ID to the appropriate row of data
   - changes the data column names to descriptive names
   - changes the activity data to descriptive names
   - produces an aggregated tidy data file of activities by subject
