Report

1. In this exercise our purpose was to estimate how a particular organization could get a loan. To reach that goal we analyzed the charity dataset.


2. 
•	The targets variables of the model are the y variables: 'IS_SUCCESSFUL' 
 

•	Besides our target variables and the EIN & NAME that we dropped, everything else specifically the features variables are our input X variables. 

 
•	We removed our input data are EIN and Name. In fact they don't have an impact on the target outcome

•	In the first attempt, I used 3 layers with 80, 30 and 1 neurons respectively. For the activation, I used ‘relu’ on my 1st and 2nd layers and sigmoid on my output layer.
 

By doing so I achieved an accuracy of 72.88%
 

•	Unfortunately, I was not able to reach the target model performance of 75%. In the second attempt I added another hidden layer with a "relu” activation while maintaining the number of nodes about the same but was only able to achieve 73.67% accuracy 

•	In the 3rd attempt I updated the first hidden layer with a different unit: 70; second hidden layer: 60 and the output layer remained 1

After the 3 attempts I will keep making some changes to see how best I can get to an optimized model