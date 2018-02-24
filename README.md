# GETTING-AND-CLEANING-DATA
# PEERED ASSIGNMENT
# OUTPUT:-
The tidy data set a set of variables for each activity and each subject. 10299 instances are split into 180 groups (30 subjects and 6 activities) and 66 mean and standard deviation features are averaged for each group. The resulting data table has 180 rows and 69 columns – 33 Mean variables + 33 Standard deviation variables + 1 Subject( 1 of of the 30 test subjects) + ActivityName + ActivityNum . The tidy data set’s first row is the header containing the names for each column.
# VARIABLES:-
# Appropriately labels the data set with descriptive variable names.
  t or f is based on time or frequency measurements.
#Body = related to body movement.
 Gravity = acceleration of gravity
 Acc = accelerometer measurement
Gyro = gyroscopic measurements
Jerk = sudden movement acceleration
 Mag = magnitude of movement
 mean and SD are calculated for each subject for each activity for each mean and SD measurements. The units given are g’s for the accelerometer and rad/sec for the gyro and g/sec and rad/sec/sec for the corresponding jerks.
 # METHOD
 'The experiments have been carried out with a group of 30 volunteers within an age bracket of 19-48 years. Each person performed six activities (WALKING, WALKING_UPSTAIRS, WALKING_DOWNSTAIRS, SITTING, STANDING, LAYING) wearing a smartphone (Samsung Galaxy S II) on the waist. Using its embedded accelerometer and gyroscope, we captured 3-axial linear acceleration and 3-axial angular velocity at a constant rate of 50Hz. The experiments have been video-recorded to label the data manually. The obtained dataset has been randomly partitioned into two sets, where 70% of the volunteers was selected for generating the training data and 30% the test data.
The sensor signals (accelerometer and gyroscope) were pre-processed by applying noise filters and then sampled in fixed-width sliding windows of 2.56 sec and 50% overlap (128 readings/window). The sensor acceleration signal, which has gravitational and body motion components, was separated using a Butterworth low-pass filter into body acceleration and gravity. The gravitational force is assumed to have only low frequency components, therefore a filter with 0.3 Hz cutoff frequency was used. From each window, a vector of features was obtained by calculating variables from the time and frequency domain.
The dataset has separate text files of training and test sets, feature vectors, and activity labels. These raw datasets are to be cleaned or arranged for the data to be properly processed and comprehensive. The goal of cleaning the dataset is to summarize the training and test sets by computing the average of each variables (feature vectors) for each activity and each subject.
