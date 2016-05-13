Feature Selection 
=================

The features selected for this database come from the accelerometer and gyroscope 3-axial raw signals tAcc-XYZ and tGyro-XYZ. These time domain signals (prefix 't' to denote time) were captured at a constant rate of 50 Hz. Then they were filtered using a median filter and a 3rd order low pass Butterworth filter with a corner frequency of 20 Hz to remove noise. Similarly, the acceleration signal was then separated into body and gravity acceleration signals (tBodyAcc-XYZ and tGravityAcc-XYZ) using another low pass Butterworth filter with a corner frequency of 0.3 Hz. 

Subsequently, the body linear acceleration and angular velocity were derived in time to obtain Jerk signals (tBodyAccJerk-XYZ and tBodyGyroJerk-XYZ). Also the magnitude of these three-dimensional signals were calculated using the Euclidean norm (tBodyAccMag, tGravityAccMag, tBodyAccJerkMag, tBodyGyroMag, tBodyGyroJerkMag). 

Finally a Fast Fourier Transform (FFT) was applied to some of these signals producing fBodyAcc-XYZ, fBodyAccJerk-XYZ, fBodyGyro-XYZ, fBodyAccJerkMag, fBodyGyroMag, fBodyGyroJerkMag. (Note the 'f' to indicate frequency domain signals). 

These signals were used to estimate variables of the feature vector for each pattern:  
'-XYZ' is used to denote 3-axial signals in the X, Y and Z directions.

tBodyAcc-XYZ
tGravityAcc-XYZ
tBodyAccJerk-XYZ
tBodyGyro-XYZ
tBodyGyroJerk-XYZ
tBodyAccMag
tGravityAccMag
tBodyAccJerkMag
tBodyGyroMag
tBodyGyroJerkMag
fBodyAcc-XYZ
fBodyAccJerk-XYZ
fBodyGyro-XYZ
fBodyAccMag
fBodyAccJerkMag
fBodyGyroMag
fBodyGyroJerkMag

The set of variables that were estimated from these signals are: 

mean(): Mean value
std(): Standard deviation
mad(): Median absolute deviation 
max(): Largest value in array
min(): Smallest value in array
sma(): Signal magnitude area
energy(): Energy measure. Sum of the squares divided by the number of values. 
iqr(): Interquartile range 
entropy(): Signal entropy
arCoeff(): Autorregresion coefficients with Burg order equal to 4
correlation(): correlation coefficient between two signals
maxInds(): index of the frequency component with largest magnitude
meanFreq(): Weighted average of the frequency components to obtain a mean frequency
skewness(): skewness of the frequency domain signal 
kurtosis(): kurtosis of the frequency domain signal 
bandsEnergy(): Energy of a frequency interval within the 64 bins of the FFT of each window.
angle(): Angle between to vectors.

Additional vectors obtained by averaging the signals in a signal window sample. These are used on the angle() variable:

gravityMean
tBodyAccMean
tBodyAccJerkMean
tBodyGyroMean
tBodyGyroJerkMean

The complete list of variables of each feature vector is available in 'features.txt'
## Codebook for Tidy Data 
This section describes the variables of tidy data(tidy_data.txt) generated as a part of Course Project

subject                                               =   Subject Who Performed the Experiment

activity                                              =   Activity (WALKING, WALKING_UPSTAIRS,WALKING_DOWNSTAIRS,SITTING,STANDING LAYING) 

TimeBodyAccelerometer.mean().X                        =   Mean Value for the Measure Grouped by Subject and Actity

TimeBodyAccelerometer.mean().Y                        =   Mean Value for the Measure Grouped by Subject and Actity

TimeBodyAccelerometer.mean().Z                        =   Mean Value for the Measure Grouped by Subject and Actity

TimeBodyAccelerometer.std().X                         =   Mean Value for the Measure Grouped by Subject and Actity

TimeBodyAccelerometer.std().Y                         =   Mean Value for the Measure Grouped by Subject and Actity

TimeBodyAccelerometer.std().Z                         =   Mean Value for the Measure Grouped by Subject and Actity

TimeGravityAccelerometer.mean().X                     =   Mean Value for the Measure Grouped by Subject and Actity

TimeGravityAccelerometer.mean().Y                     =   Mean Value for the Measure Grouped by Subject and Actity

TimeGravityAccelerometer.mean().Z                     =   Mean Value for the Measure Grouped by Subject and Actity

TimeGravityAccelerometer.std().X                      =   Mean Value for the Measure Grouped by Subject and Actity

TimeGravityAccelerometer.std().Y                      =   Mean Value for the Measure Grouped by Subject and Actity

TimeGravityAccelerometer.std().Z                      =   Mean Value for the Measure Grouped by Subject and Actity

TimeBodyAccelerometerJerk.mean().X                    =   Mean Value for the Measure Grouped by Subject and Actity

TimeBodyAccelerometerJerk.mean().Y                    =   Mean Value for the Measure Grouped by Subject and Actity

TimeBodyAccelerometerJerk.mean().Z                    =   Mean Value for the Measure Grouped by Subject and Actity

TimeBodyAccelerometerJerk.std().X                     =   Mean Value for the Measure Grouped by Subject and Actity

TimeBodyAccelerometerJerk.std().Y                     =   Mean Value for the Measure Grouped by Subject and Actity

TimeBodyAccelerometerJerk.std().Z                     =   Mean Value for the Measure Grouped by Subject and Actity

TimeBodyGyroscope.mean().X                            =   Mean Value for the Measure Grouped by Subject and Actity

TimeBodyGyroscope.mean().Y                            =   Mean Value for the Measure Grouped by Subject and Actity

TimeBodyGyroscope.mean().Z                            =   Mean Value for the Measure Grouped by Subject and Actity

TimeBodyGyroscope.std().X                             =   Mean Value for the Measure Grouped by Subject and Actity

TimeBodyGyroscope.std().Y                             =   Mean Value for the Measure Grouped by Subject and Actity

TimeBodyGyroscope.std().Z                             =   Mean Value for the Measure Grouped by Subject and Actity

TimeBodyGyroscopeJerk.mean().X                        =   Mean Value for the Measure Grouped by Subject and Actity

TimeBodyGyroscopeJerk.mean().Y                        =   Mean Value for the Measure Grouped by Subject and Actity

TimeBodyGyroscopeJerk.mean().Z                        =   Mean Value for the Measure Grouped by Subject and Actity

TimeBodyGyroscopeJerk.std().X                         =   Mean Value for the Measure Grouped by Subject and Actity

TimeBodyGyroscopeJerk.std().Y                         =   Mean Value for the Measure Grouped by Subject and Actity

TimeBodyGyroscopeJerk.std().Z                         =   Mean Value for the Measure Grouped by Subject and Actity

TimeBodyAccelerometerMagnitude.mean()                 =   Mean Value for the Measure Grouped by Subject and Actity

TimeBodyAccelerometerMagnitude.std()                  =   Mean Value for the Measure Grouped by Subject and Actity

TimeGravityAccelerometerMagnitude.mean()              =   Mean Value for the Measure Grouped by Subject and Actity

TimeGravityAccelerometerMagnitude.std()               =   Mean Value for the Measure Grouped by Subject and Actity

TimeBodyAccelerometerJerkMagnitude.mean()             =   Mean Value for the Measure Grouped by Subject and Actity

TimeBodyAccelerometerJerkMagnitude.std()              =   Mean Value for the Measure Grouped by Subject and Actity

TimeBodyGyroscopeMagnitude.mean()                     =   Mean Value for the Measure Grouped by Subject and Actity

TimeBodyGyroscopeMagnitude.std()                      =   Mean Value for the Measure Grouped by Subject and Actity

TimeBodyGyroscopeJerkMagnitude.mean()                 =   Mean Value for the Measure Grouped by Subject and Actity

TimeBodyGyroscopeJerkMagnitude.std()                  =   Mean Value for the Measure Grouped by Subject and Actity

FrequencyBodyAccelerometer.mean().X                   =   Mean Value for the Measure Grouped by Subject and Actity

FrequencyBodyAccelerometer.mean().Y                   =   Mean Value for the Measure Grouped by Subject and Actity

FrequencyBodyAccelerometer.mean().Z                   =   Mean Value for the Measure Grouped by Subject and Actity

FrequencyBodyAccelerometer.std().X                    =   Mean Value for the Measure Grouped by Subject and Actity

FrequencyBodyAccelerometer.std().Y                    =   Mean Value for the Measure Grouped by Subject and Actity

FrequencyBodyAccelerometer.std().Z                    =   Mean Value for the Measure Grouped by Subject and Actity

FrequencyBodyAccelerometer.meanFreq().X               =   Mean Value for the Measure Grouped by Subject and Actity

FrequencyBodyAccelerometer.meanFreq().Y               =   Mean Value for the Measure Grouped by Subject and Actity

FrequencyBodyAccelerometer.meanFreq().Z               =   Mean Value for the Measure Grouped by Subject and Actity

FrequencyBodyAccelerometerJerk.mean().X               =   Mean Value for the Measure Grouped by Subject and Actity

FrequencyBodyAccelerometerJerk.mean().Y               =   Mean Value for the Measure Grouped by Subject and Actity

FrequencyBodyAccelerometerJerk.mean().Z               =   Mean Value for the Measure Grouped by Subject and Actity

FrequencyBodyAccelerometerJerk.std().X                =   Mean Value for the Measure Grouped by Subject and Actity

FrequencyBodyAccelerometerJerk.std().Y                =   Mean Value for the Measure Grouped by Subject and Actity

FrequencyBodyAccelerometerJerk.std().Z                =   Mean Value for the Measure Grouped by Subject and Actity

FrequencyBodyAccelerometerJerk.meanFreq().X           =   Mean Value for the Measure Grouped by Subject and Actity

FrequencyBodyAccelerometerJerk.meanFreq().Y           =   Mean Value for the Measure Grouped by Subject and Actity

FrequencyBodyAccelerometerJerk.meanFreq().Z           =   Mean Value for the Measure Grouped by Subject and Actity

FrequencyBodyGyroscope.mean().X                       =   Mean Value for the Measure Grouped by Subject and Actity

FrequencyBodyGyroscope.mean().Y                       =   Mean Value for the Measure Grouped by Subject and Actity

FrequencyBodyGyroscope.mean().Z                       =   Mean Value for the Measure Grouped by Subject and Actity

FrequencyBodyGyroscope.std().X                        =   Mean Value for the Measure Grouped by Subject and Actity

FrequencyBodyGyroscope.std().Y                        =   Mean Value for the Measure Grouped by Subject and Actity

FrequencyBodyGyroscope.std().Z                        =   Mean Value for the Measure Grouped by Subject and Actity

FrequencyBodyGyroscope.meanFreq().X                   =   Mean Value for the Measure Grouped by Subject and Actity

FrequencyBodyGyroscope.meanFreq().Y                   =   Mean Value for the Measure Grouped by Subject and Actity

FrequencyBodyGyroscope.meanFreq().Z                   =   Mean Value for the Measure Grouped by Subject and Actity

FrequencyBodyAccelerometerMagnitude.mean()            =   Mean Value for the Measure Grouped by Subject and Actity

FrequencyBodyAccelerometerMagnitude.std()             =   Mean Value for the Measure Grouped by Subject and Actity

FrequencyBodyAccelerometerMagnitude.meanFreq()        =   Mean Value for the Measure Grouped by Subject and Actity

FrequencyBodyAccelerometerJerkMagnitude.mean()        =   Mean Value for the Measure Grouped by Subject and Actity

FrequencyBodyAccelerometerJerkMagnitude.std()         =   Mean Value for the Measure Grouped by Subject and Actity

FrequencyBodyAccelerometerJerkMagnitude.meanFreq()    =   Mean Value for the Measure Grouped by Subject and Actity

FrequencyBodyGyroscopeMagnitude.mean()                =   Mean Value for the Measure Grouped by Subject and Actity

FrequencyBodyGyroscopeMagnitude.std()                 =   Mean Value for the Measure Grouped by Subject and Actity

FrequencyBodyGyroscopeMagnitude.meanFreq()            =   Mean Value for the Measure Grouped by Subject and Actity

FrequencyBodyGyroscopeJerkMagnitude.mean()            =   Mean Value for the Measure Grouped by Subject and Actity

FrequencyBodyGyroscopeJerkMagnitude.std()             =   Mean Value for the Measure Grouped by Subject and Actity

FrequencyBodyGyroscopeJerkMagnitude.meanFreq()        =   Mean Value for the Measure Grouped by Subject and Actity

angle(tBodyAccelerometerMean,gravity)                 =   Mean Value for the Measure Grouped by Subject and Actity

angle(tBodyAccelerometerJerkMean),gravityMean)        =   Mean Value for the Measure Grouped by Subject and Actity

angle(tBodyGyroscopeMean,gravityMean)                 =   Mean Value for the Measure Grouped by Subject and Actity

angle(tBodyGyroscopeJerkMean,gravityMean)             =   Mean Value for the Measure Grouped by Subject and Actity

angle(X,gravityMean)                                  =   Mean Value for the Measure Grouped by Subject and Actity

angle(Y,gravityMean)                                  =   Mean Value for the Measure Grouped by Subject and Actity

angle(Z,gravityMean)                                  =   Mean Value for the Measure Grouped by Subject and Actity
