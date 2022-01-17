# tomato_classification

Data source : https://www.kaggle.com/olgabelitskaya/tomato-cultivars  

In the above kaggle data set , there are 15 types of tomato images.Number of images are 776.   
This is an attempt to classify the images with the best possible accuracy.   

Transfer Learning using Pre Trained Model - ResNet50.  
The initial attempts to build a Neural Network based classifier in Tensorflow  gave a poor accuracy of 0.47.  

Hence sought out the help of transfer learning using various pre trained models provided in keras/application.

Among all the models , ResNet50 gave the highest accuracy. Hence in the above notebooks , the images are sliced into different set of train/validate/test images and the using the same config of the model , the accuracy is checked. Variance of the model is understood.   
