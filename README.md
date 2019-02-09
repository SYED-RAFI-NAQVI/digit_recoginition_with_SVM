# Digit_recoginition_with_SVM



  # Importing packages
  
  Import the required packages. Numpy, Matplotlib are essential packages for data cleaning and data visualizing.
  Scikit-Learn library provides numerously supervised and unsupervised algorithms. import SVM (support vector machine) from  
  sci-kit-learn for the classification. import required dataset, which provides by the sci-kit-learn or from any kaggel   
  repositories.
  
  
  # Loading datasets
  Loading a dataset is grabbing the data in the current workflow. check the data with Numpy for additional information, 
  digits dataset is in key and value pairs, we can grab the data with dot notation. the dataset has the training data and 
  test data, can use the test data to test how our predictions are going on.
  
  
  # classifier
  
  In the project, we choose SVC (support vector classifier) the classifier to classify the given data set. we are passing just 
  two parameters gamma and C. gamma ==> learning rate and C ==> optimization. the learning rate is, how fast algorithm is 
  learning from the given data. if it is very fast it may occur with many errors, so the learning rate should be slow. C 
  take care about the optimization of the data. for more info check out https://stats.stackexchange.com/posts/159051/revisions
  
  
  # splitting and fitting the data
  
  split the data into training and test data. train data used to train our machine learning model, test data used to test the
  data after training the machine learning model to check how accurate the model predicting. fitting the data into the 
  model where the classification takes place, the word behind this is Gradient decent helps to attain the least mean square
  error. 
  
  # prediction 
  
  finally, predict the value if all works well then the model predicts the accurate values...!
