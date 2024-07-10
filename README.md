# Neural-Network-ICP3
This repo contains python notebook files for ICP3
  a) ICP3-Cancer_detection.ipynb file contains code to determine the following.
  1. Add more Dense layers to the existing code and check how the accuracy changes.
  2. Change the data source to Breast Cancer dataset available in the source code folder and make required
     changes. Report accuracy of the model.
  3. Normalize the data before feeding the data to the model and check how the normalization change your accuracy
     from sklearn.preprocessing import StandardScaler
     sc = StandardScaler()

  b) Use Image Classification on the hand written digits data set (mnist)
  1. Plot the loss and accuracy for both training data and validation data using the history object in the source
     code.
  2. Plot one of the images in the test data, and then do inferencing to check what is the prediction of the model
     on that single image.
  3. We had used 2 hidden layers and Relu activation. Try to change the number of hidden layer and the
     activation to tanh or sigmoid and see what happens.
  4. Run the same code without scaling the images and check the performance?
