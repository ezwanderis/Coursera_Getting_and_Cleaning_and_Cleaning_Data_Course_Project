## Code Book for Coursera Getting and Cleaning Data Course Project

### Raw Data
A full description is available at the site where the data was obtained: 
http://archive.ics.uci.edu/ml/datasets/Human+Activity+Recognition+Using+Smartphones 

Here are the data for the project:
https://d396qusza40orc.cloudfront.net/getdata%2Fprojectfiles%2FUCI%20HAR%20Dataset.zip 

### Data Cleaning

The raw data is cleaned and tidied with the purpose to collect, work with, and clean the data set. The goal is to prepare tidy data that can be used for later analysis using the "run_analysis.R" script that is provided.

The "run_analysis.R" script does the following instructions:

1. Merges the training and the test sets to create one data set.
2. Extracts only the measurements on the mean and standard deviation for each measurement. 
3. Uses descriptive activity names to name the activities in the data set
4. Appropriately labels the data set with descriptive variable names. 
5. From the data set in step 4, creates a second, independent tidy data set with the average of each variable for each activity and each subject.

### The Clean Data
The resulting data set has these set of columns/variables:

1 subject.id : The subject ID, an integer in the range 1:30
2 activity : The activity performed by the subject

 $ subject  : The subject ID, an integer
 $ activity : The activity performed by the subject
 $ tBodyAccMeanX           
 $ tBodyAccMeanY           
 $ tBodyAccMeanZ           
 $ tBodyAccStdX            
 $ tBodyAccStdY            
 $ tBodyAccStdZ            
 $ tGravityAccMeanX        
 $ tGravityAccMeanY        
 $ tGravityAccMeanZ        
 $ tGravityAccStdX         
 $ tGravityAccStdY         
 $ tGravityAccStdZ         
 $ tBodyAccJerkMeanX       
 $ tBodyAccJerkMeanY       
 $ tBodyAccJerkMeanZ       
 $ tBodyAccJerkStdX        
 $ tBodyAccJerkStdY        
 $ tBodyAccJerkStdZ        
 $ tBodyGyroMeanX          
 $ tBodyGyroMeanY          
 $ tBodyGyroMeanZ          
 $ tBodyGyroStdX           
 $ tBodyGyroStdY           
 $ tBodyGyroStdZ           
 $ tBodyGyroJerkMeanX      
 $ tBodyGyroJerkMeanY      
 $ tBodyGyroJerkMeanZ      
 $ tBodyGyroJerkStdX       
 $ tBodyGyroJerkStdY       
 $ tBodyGyroJerkStdZ       
 $ tBodyAccMagMean         
 $ tBodyAccMagStd          
 $ tGravityAccMagMean      
 $ tGravityAccMagStd       
 $ tBodyAccJerkMagMean     
 $ tBodyAccJerkMagStd      
 $ tBodyGyroMagMean        
 $ tBodyGyroMagStd         
 $ tBodyGyroJerkMagMean    
 $ tBodyGyroJerkMagStd     
 $ fBodyAccMeanX           
 $ fBodyAccMeanY           
 $ fBodyAccMeanZ           
 $ fBodyAccStdX            
 $ fBodyAccStdY            
 $ fBodyAccStdZ            
 $ fBodyAccJerkMeanX       
 $ fBodyAccJerkMeanY       
 $ fBodyAccJerkMeanZ       
 $ fBodyAccJerkStdX        
 $ fBodyAccJerkStdY        
 $ fBodyAccJerkStdZ        
 $ fBodyGyroMeanX          
 $ fBodyGyroMeanY          
 $ fBodyGyroMeanZ          
 $ fBodyGyroStdX           
 $ fBodyGyroStdY           
 $ fBodyGyroStdZ           
 $ fBodyAccMagMean         
 $ fBodyAccMagStd          
 $ fBodyBodyAccJerkMagMean 
 $ fBodyBodyAccJerkMagStd  
 $ fBodyBodyGyroMagMean    
 $ fBodyBodyGyroMagStd     
 $ fBodyBodyGyroJerkMagMean
 $ fBodyBodyGyroJerkMagStd 

### Result
The result, produced and written in a file "tidydata.txt"