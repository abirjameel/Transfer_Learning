# Transfer_Learning
Transfer learning is a machine learning method where a model developed for a task is reused as the starting point for a model on a second task.
Since it is difficult to train a deep learning network from sratch, this is a wonderful technique to use pretrained networks as a starting point. 
## How it works 
In this tutorial you will be going to use Inception V3 for retraining it on new classes, in simple words it can be thought as a feature extracter for your dataset. 
This starts with loading pretrained model using TensorFlow `save` and `restore`, then you have to freeze the model add a layer for your outputs instead of 1000 classes you definitely want some different number of classes, and the last thing is to retrain the model for your bottleneck of or last layer of network. 

# References 
Following blogs and repos are of utmost help while writing this tutorial.   
https://codelabs.developers.google.com/codelabs/tensorflow-for-poets/#0
https://machinelearningmastery.com/transfer-learning-for-deep-learning/
