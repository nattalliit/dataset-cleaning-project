## Getting and Cleaning Data Project
### Description
Additional information about the variables, data and transformations used in the course project for the Johns Hopkins Getting and Cleaning Data course.

### Source Data
Data + Description can be found here [UCI Machine Learning Repository](http://archive.ics.uci.edu/ml/datasets/Human+Activity+Recognition+Using+Smartphones)

### Data Set Information
The experiments involved 30 volunteers aged between 19 and 48 years. Each participant engaged in six activities (WALKING, WALKING_UPSTAIRS, WALKING_DOWNSTAIRS, SITTING, STANDING, LAYING), wearing a Samsung Galaxy S II smartphone on their waist. This device, equipped with an accelerometer and gyroscope, recorded 3-axial linear acceleration and 3-axial angular velocity at a consistent rate of 50Hz. Video recordings were used to manually label the data collected from these experiments. 

The dataset obtained was randomly divided into two subsets: 70% for training data and 30% for testing data, selected from the volunteers.

The sensor signals from the accelerometer and gyroscope underwent preprocessing, which included noise filtering and sampling in fixed-width sliding windows of 2.56 seconds with a 50% overlap (resulting in 128 readings per window). The accelerometer signal was further processed using a Butterworth low-pass filter to separate gravitational and body motion components. A filter with a 0.3 Hz cutoff frequency was applied to isolate the gravitational force, which predominantly contains low-frequency components. 

From each window of data, a feature vector was derived by computing various variables from both the time and frequency domains.


### Attribute Information
For each record in the dataset it is provided: 
- Triaxial acceleration from the accelerometer (total acceleration) and the estimated body acceleration. 
- Triaxial Angular velocity from the gyroscope. 
- A 561-feature vector with time and frequency domain variables. 
- Its activity label. 
- An identifier of the subject who carried out the experiment.

## Please see the README.md for how the following instructions are implemented [README.md](https://github.com/nattalliit/dataset-cleaning-project/blob/main/README.md)
### 1. Merge the training and the test sets to create one data set.
### 2. Extracts only the measurements on the mean and standard deviation for each measurement.
### 3. Uses descriptive activity names to name the activities in the data set
### 4. Appropriately labels the data set with descriptive variable names.
### 5. From the data set in step 4, creates other independent tidy data set with the average of each variable for each activity and each subject.