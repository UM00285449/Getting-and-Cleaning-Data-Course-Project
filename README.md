Get the data
1.Download the file and put the file in the data folder
2.Unzip the file
3.unzipped files are in the folderUCI HAR Dataset. Get the list of the files
Read data from the targeted files
2.Read data from the files into the variables
Read the Activity files
Read the Subject files
Read Fearures files
3.	Look at the properties of the above varibles
Merges the training and the test sets to create one data set
1.Concatenate the data tables by rows
2.set names to variables
3.Merge columns to get the data frame Data for all data
Extracts only the measurements on the mean and standard deviation for each measurement
1.	Subset Name of Features by measurements on the mean and standard deviation
2.	Subset the data frame Data by seleted names of Features
3.	Check the structures of the data frame Data
Uses descriptive activity names to name the activities in the data set
1.Read descriptive activity names from “activity_labels.txt”
2.	facorize Variale activity in the data frame Data using descriptive activity names
3.	check
Appropriately labels the data set with descriptive variable names
In the former part, variables activity and subject and names of the activities have been labelled using descriptive names.In this part, Names of Feteatures will labelled using descriptive variable names.
•	prefix t is replaced by time
•	Acc is replaced by Accelerometer
•	Gyro is replaced by Gyroscope
•	prefix f is replaced by frequency
•	Mag is replaced by Magnitude
•	BodyBody is replaced by Body
Creates a second,independent tidy data set and ouput it
In this part,a second, independent tidy data set will be created with the average of each variable for each activity and each subject based on the data set in step 4.
