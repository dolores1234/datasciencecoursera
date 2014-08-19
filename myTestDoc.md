### Code book for tidy.txt datafile

format of code book is:

column	variable name
        description
        value(s)                                                 
There a 68 variables in the datafile.
   1	activity                             	   				      
     	A variable length character description of the measured activity.                
        Values:
        - WALKING                                                                      
        - WALKING_UPSTAIRS                                                                
    	- WALKING_DOWNSTAIRS                                                              
     	- SITTING                                                                         
     	- STANDING                                                                        
     	- LAYING                                                                          
               
    2  subject                                                                           
       An integer value assigned to each participant in the student.                     
       Value range: [1:30]  
       
The following 66 variables are the mean of measurements.        
                                                                                       
    3  tBodyAccMeanX                                                                     
       The mean time domain signal of the body acceleration in the X-axis direction.     
                                                                                       
    4  tBodyAccMeanY                                                                     
       The mean time domain signal of the body acceleration in the Y-axis direction.     
                                                                                       
    5  tBodyAccMeanZ                                                                     
       The mean time domain signal of the body acceleration in the Z-axis direction.     