{\rtf1\ansi\ansicpg936\cocoartf1404\cocoasubrtf470
{\fonttbl\f0\fnil\fcharset0 HelveticaNeue;}
{\colortbl;\red255\green255\blue255;\red38\green38\blue38;\red50\green98\blue178;}
{\*\listtable{\list\listtemplateid1\listhybrid{\listlevel\levelnfc23\levelnfcn23\leveljc0\leveljcn0\levelfollow0\levelstartat1\levelspace360\levelindent0{\*\levelmarker \{disc\}}{\leveltext\leveltemplateid1\'01\uc0\u8226 ;}{\levelnumbers;}\fi-360\li720\lin720 }{\listname ;}\listid1}
{\list\listtemplateid2\listhybrid{\listlevel\levelnfc23\levelnfcn23\leveljc0\leveljcn0\levelfollow0\levelstartat1\levelspace360\levelindent0{\*\levelmarker \{disc\}}{\leveltext\leveltemplateid101\'01\uc0\u8226 ;}{\levelnumbers;}\fi-360\li720\lin720 }{\listname ;}\listid2}
{\list\listtemplateid3\listhybrid{\listlevel\levelnfc23\levelnfcn23\leveljc0\leveljcn0\levelfollow0\levelstartat1\levelspace360\levelindent0{\*\levelmarker \{disc\}}{\leveltext\leveltemplateid201\'01\uc0\u8226 ;}{\levelnumbers;}\fi-360\li720\lin720 }{\listname ;}\listid3}
{\list\listtemplateid4\listhybrid{\listlevel\levelnfc0\levelnfcn0\leveljc0\leveljcn0\levelfollow0\levelstartat1\levelspace360\levelindent0{\*\levelmarker \{decimal\}}{\leveltext\leveltemplateid301\'01\'00;}{\levelnumbers\'01;}\fi-360\li720\lin720 }{\listname ;}\listid4}}
{\*\listoverridetable{\listoverride\listid1\listoverridecount0\ls1}{\listoverride\listid2\listoverridecount0\ls2}{\listoverride\listid3\listoverridecount0\ls3}{\listoverride\listid4\listoverridecount0\ls4}}
\paperw11900\paperh16840\margl1440\margr1440\vieww10800\viewh8400\viewkind0
\deftab720
\pard\pardeftab720\partightenfactor0

\f0\b\fs64 \cf2 \expnd0\expndtw0\kerning0
CodeBook\
\pard\pardeftab720\partightenfactor0

\b0\fs32 \cf2 This is a code book that describes the variables, the data, and any transformations or work that you performed to clean up the data.\
\pard\pardeftab720\partightenfactor0

\b\fs48 \cf3 \
\pard\pardeftab720\partightenfactor0
\cf2 The data source\
\pard\tx220\tx720\pardeftab720\li720\fi-720\partightenfactor0
\ls1\ilvl0
\b0\fs32 \cf2 \kerning1\expnd0\expndtw0 {\listtext	\'95	}\expnd0\expndtw0\kerning0
Original data: {\field{\*\fldinst{HYPERLINK "https://d396qusza40orc.cloudfront.net/getdata%2Fprojectfiles%2FUCI%20HAR%20Dataset.zip"}}{\fldrslt \cf3 https://d396qusza40orc.cloudfront.net/getdata%2Fprojectfiles%2FUCI%20HAR%20Dataset.zip}}\
\ls1\ilvl0\kerning1\expnd0\expndtw0 {\listtext	\'95	}\expnd0\expndtw0\kerning0
Original description of the dataset: {\field{\*\fldinst{HYPERLINK "http://archive.ics.uci.edu/ml/datasets/Human+Activity+Recognition+Using+Smartphones"}}{\fldrslt \cf3 http://archive.ics.uci.edu/ml/datasets/Human+Activity+Recognition+Using+Smartphones}}\
\pard\pardeftab720\partightenfactor0
\cf2 \
\pard\pardeftab720\partightenfactor0

\b\fs48 \cf3 \
\pard\pardeftab720\partightenfactor0
\cf2 The data\
\pard\pardeftab720\partightenfactor0

\b0\fs32 \cf2 The dataset includes the following files:\
\pard\tx220\tx720\pardeftab720\li720\fi-720\partightenfactor0
\ls2\ilvl0\cf2 \kerning1\expnd0\expndtw0 {\listtext	\'95	}\expnd0\expndtw0\kerning0
'README.txt'\
\ls2\ilvl0\kerning1\expnd0\expndtw0 {\listtext	\'95	}\expnd0\expndtw0\kerning0
'features_info.txt': Shows information about the variables used on the feature vector.\
\ls2\ilvl0\kerning1\expnd0\expndtw0 {\listtext	\'95	}\expnd0\expndtw0\kerning0
'features.txt': List of all features.\
\ls2\ilvl0\kerning1\expnd0\expndtw0 {\listtext	\'95	}\expnd0\expndtw0\kerning0
'activity_labels.txt': Links the class labels with their activity name.\
\ls2\ilvl0\kerning1\expnd0\expndtw0 {\listtext	\'95	}\expnd0\expndtw0\kerning0
'train/X_train.txt': Training set.\
\ls2\ilvl0\kerning1\expnd0\expndtw0 {\listtext	\'95	}\expnd0\expndtw0\kerning0
'train/y_train.txt': Training labels.\
\ls2\ilvl0\kerning1\expnd0\expndtw0 {\listtext	\'95	}\expnd0\expndtw0\kerning0
'test/X_test.txt': Test set.\
\ls2\ilvl0\kerning1\expnd0\expndtw0 {\listtext	\'95	}\expnd0\expndtw0\kerning0
'test/y_test.txt': Test labels.\
\pard\pardeftab720\partightenfactor0
\cf2 The following files are available for the train and test data. Their descriptions are equivalent.\
\pard\tx220\tx720\pardeftab720\li720\fi-720\partightenfactor0
\ls3\ilvl0\cf2 \kerning1\expnd0\expndtw0 {\listtext	\'95	}\expnd0\expndtw0\kerning0
'train/subject_train.txt': Each row identifies the subject who performed the activity for each window sample. Its range is from 1 to 30.\
\ls3\ilvl0\kerning1\expnd0\expndtw0 {\listtext	\'95	}\expnd0\expndtw0\kerning0
'train/Inertial Signals/total_acc_x_train.txt': The acceleration signal from the smartphone accelerometer X axis in standard gravity units 'g'. Every row shows a 128 element vector. The same description applies for the 'total_acc_x_train.txt' and 'total_acc_z_train.txt' files for the Y and Z axis.\
\ls3\ilvl0\kerning1\expnd0\expndtw0 {\listtext	\'95	}\expnd0\expndtw0\kerning0
'train/Inertial Signals/body_acc_x_train.txt': The body acceleration signal obtained by subtracting the gravity from the total acceleration.\
\ls3\ilvl0\kerning1\expnd0\expndtw0 {\listtext	\'95	}\expnd0\expndtw0\kerning0
'train/Inertial Signals/body_gyro_x_train.txt': The angular velocity vector measured by the gyroscope for each window sample. The units are radians/second.\
\pard\pardeftab720\partightenfactor0

\b\fs48 \cf3 \
\pard\pardeftab720\partightenfactor0
\cf2 Transformation details\
\pard\pardeftab720\partightenfactor0

\b0\fs32 \cf2 There are 5 parts:\
\pard\tx220\tx720\pardeftab720\li720\fi-720\partightenfactor0
\ls4\ilvl0\cf2 \kerning1\expnd0\expndtw0 {\listtext	1	}
\fs28 \cf2 1	\expnd0\expndtw0\kerning0
Merges the training and the test sets to create one data set.\
\pard\tx220\tx720\pardeftab720\li720\fi-720\partightenfactor0
\ls4\ilvl0\cf2 \kerning1\expnd0\expndtw0 {\listtext	2	}\expnd0\expndtw0\kerning0
Extracts only the measurements on the mean and standard deviation for each measurement.\
\ls4\ilvl0\kerning1\expnd0\expndtw0 {\listtext	3	}\expnd0\expndtw0\kerning0
Uses descriptive activity names to name the activities in the data set\
\ls4\ilvl0\kerning1\expnd0\expndtw0 {\listtext	4	}\expnd0\expndtw0\kerning0
Appropriately labels the data set with descriptive variable names.\
\ls4\ilvl0\kerning1\expnd0\expndtw0 {\listtext	5	}\expnd0\expndtw0\kerning0
From the data set in step 4, creates a second, independent tidy data set with the average of each variable for each activity and each subject.}