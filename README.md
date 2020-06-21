# Machine-Learning-for-Human-Activity-Recognition

This project attempts to search and apply effective methods to analyze and recognize human activities by the inertial signal data collected from the sensors in smartphones. We are trying to build four possible classifiers gained by Random Forest
Tree (RF), K Nearest Neighbors (KNN), Artificial Neural Network (ANN) and Support Vector Machine (SVM) respectively. Meanwhile, exploreing how dimension reduction affect the classifier’s performance by using Principle Component Analysis (PCA). Last but not least, we try to find the best parameters of these four models with the help of cross validation.

Data Description:  
  
The data set was downloaded from UCI Machine Repository(https://archive.ics.uci.edu/ml/datasets/Human+Activity+Recognition+Using+Smartphones). 
In this experiment, researchers set six labels including standing, sitting, lying, walking, walking downstairs, walking upstairs. Through the specific sensor, the velocity and acceleration of the angular and linear movement could be obtained. Specifically, these data were all in three-dimensions. There were only seventeen kinds of data we could get initially. Through mathematical calculation (a Fast Fourier Transform was used), we could get the data of the accelerometer and gyroscope in different axials (including the different combination of the axials). The total amount of the features was 561.  
  
The F1-score of test dataset are  
RF:0.90 / SVM:0.95/ ANN:0.94
